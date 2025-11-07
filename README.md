# 🎨 AI Visual Story Generator

This project converts plain text pitches into **cinematic, image-generation–ready prompts** and then creates visuals using **Stable Diffusion XL Turbo**.

---

## 🚀 Features

* Splits long text into meaningful sentences
* Enhances each sentence into a vivid, descriptive visual prompt using **Groq’s Llama 3.3–70B**
* Generates high-quality images using **SDXL Turbo**
* Saves all images in the `generated_images` folder

---

## 🧰 Requirements

Install all dependencies:

```bash
pip install torch diffusers transformers accelerate Pillow spacy langchain langchain_groq ipython
python -m spacy download en_core_web_sm
```

---

## ⚙️ How It Works

1. **Input:** A marketing or concept pitch (plain text)
2. **LLM (Groq):** Enhances each sentence into a cinematic visual prompt
3. **Diffusion Model:** Uses **SDXL Turbo** to generate high-quality visuals
4. **Output:** Images saved automatically in the `generated_images` folder

---

## 🧩 Example Pitch

```text
VeloCity is reimagining how people move through their cities.
Our AI-powered e-bikes automatically adjust speed, route, and energy based on traffic and weather.
Riders glide effortlessly through smart lanes lit by dynamic LED paths that respond to motion.
At every turn, VeloCity makes urban commuting faster, greener, and more connected.
```

---

## ▶️ Run the Notebook

```
 main.ipynb
```

This will:

* Enhance your pitch using the Groq LLM
* Generate cinematic image prompts
* Create visuals using **Stable Diffusion XL Turbo**

---

## 🖼️ Output

Generated images will be saved inside:

```
generated_images/
 ├── scene_1.png
 ├── scene_2.png
 └── ...
```

---

## 🧠 Model Used

* **LLM:** Groq `llama-3.3-70b-versatile`
* **Diffusion Model:** `stabilityai/sdxl-turbo`

---

## 📜 License

This project is open-source and free to use under the **MIT License**.

---
