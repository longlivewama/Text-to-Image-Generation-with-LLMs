
# 🖼️ Text-to-Image Generation with LLMs and Stable Diffusion & Gradio

Generate high-quality, realistic images from natural language prompts using **Stable Diffusion** models integrated with an intuitive **Gradio GUI**.
This project demonstrates how to use **LLMs, Stable Diffusion, and Diffusers** to create stunning AI-generated visuals interactively.

---

## 🚀 Project Overview

This project leverages **Hugging Face Diffusers** and **Gradio** to build a full text-to-image generation pipeline.
It allows users to input text prompts, adjust generation parameters (like inference steps, image size, and negative prompts), and visualize the results instantly.

### 🧠 Key Features

* ✅ **Stable Diffusion Integration** (`dreamlike-art/dreamlike-diffusion-1.0`)
* 🎨 **Gradio GUI** for interactive prompt-based image generation
* ⚙️ Adjustable parameters:

  * Number of inference steps
  * Image height & width
  * Number of images per prompt
  * Negative prompting
* 🧩 **GPU acceleration** with PyTorch + CUDA
* 🖼️ Support for **multiple generated images** via `gr.Gallery`

---

## 🧰 Tech Stack

| Component                | Description                                      |
| ------------------------ | ------------------------------------------------ |
| 🧠 **Stable Diffusion**  | Deep learning model for text-to-image generation |
| 💡 **Diffusers Library** | Hugging Face library for diffusion models        |
| ⚡ **PyTorch**            | Deep learning framework with CUDA support        |
| 🎛️ **Gradio**           | Easy-to-use library for creating web-based GUIs  |
| 🐍 **Python 3.10+**      | Core programming language                        |

---

## 📦 Installation

Clone this repository and install dependencies.

```bash
git clone https://github.com/<your-username>/text-to-image-generation.git
cd text-to-image-generation
```

Then install the required Python libraries:

```bash
pip install diffusers transformers accelerate gradio torch matplotlib
```

> ⚠️ **Tip:**
> For best performance, use a CUDA-enabled GPU.
> Ensure your PyTorch version supports GPU acceleration (`torch.cuda.is_available()` should return `True`).

---

## 🧩 Usage

### 1️⃣ Run the Notebook or Script

You can run the notebook in **Google Colab** or locally.

**Colab:**

```python
!pip install diffusers transformers accelerate gradio torch matplotlib
```

Then execute the cells — the Gradio app will automatically launch.

**Local:**

```bash
python text_to_image_generation.py
```

---

### 2️⃣ Launch the Gradio Interface

Once executed, you’ll see a local or public Gradio link like:

```
Running on local URL:  http://127.0.0.1:7860
Running on public URL: https://<your-gradio-link>.gradio.live
```

Open the link in your browser to start generating images!

---

## 🧠 Example Prompts

Try these example prompts in the GUI:

| Type                 | Prompt Example                                                                                                             |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| 🌆 Real-life scene   | “Generate a series of realistic photographs that capture everyday moments in a genuine and relatable manner.”              |
| 🏜️ Cultural setting | “Generate an image that encapsulates the essence of Tunisia with its intricate desert architecture and cultural richness.” |
| 🌸 Nature            | “Picturesque garden adorned with diverse, vibrant flowers in full bloom. Capture the scene’s serenity.”                    |

---

## ⚙️ Parameters in GUI

| Parameter                 | Description                                    | Default |
| ------------------------- | ---------------------------------------------- | ------- |
| **Prompt**                | The main text description for image generation | —       |
| **Negative Prompt**       | Words to avoid (e.g. “low quality, distorted”) | —       |
| **Num Inference Steps**   | Controls detail and quality                    | `50`    |
| **Height**                | Image height (px)                              | `512`   |
| **Width**                 | Image width (px)                               | `512`   |
| **Num Images per Prompt** | Number of images to generate                   | `1`     |

---

## 🧱 Project Structure

```
text-to-image-generation/
│
├── text_to_image_generation.ipynb   # Colab notebook
├── text_to_image_generation.py      # Script version (optional)
├── README.md                        # Project documentation
└── requirements.txt                 # Dependencies (optional)
```

---

## 🎯 Future Enhancements

* 🪄 Add image saving and download buttons
* 🧰 Allow multiple Stable Diffusion model choices
* 🌍 Add multilingual prompt support
* 🖌️ Implement image-to-image generation
* 🔗 Add Hugging Face Spaces deployment

---

## 🧑‍💻 Author

**Ahmed Fahim**
🎓 Faculty of Artificial Intelligence – Major in Data Science
💡 Passionate about AI, Machine Learning, and Computer Vision
🔗 [LinkedIn](https://www.linkedin.com/in/ahmed-fahim) | [GitHub](https://github.com/<your-username>)

---

## 🪪 License

This project is open source and available under the [MIT License](LICENSE).

---

## 💬 Acknowledgements

* [Hugging Face Diffusers](https://huggingface.co/docs/diffusers)
* [Stable Diffusion Models](https://huggingface.co/models)
* [Gradio](https://gradio.app)
* [PyTorch](https://pytorch.org)


