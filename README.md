# Introduction to Generative AI in watsonx.ai

## Deskripsi Project
Project ini adalah implementasi dari lab "Introduction to Generative AI" menggunakan Watson Machine Learning API dan model `google/flan-ul2`. Notebook ini menunjukkan cara kerja Large Language Models (LLMs) dengan fokus pada rekayasa prompt, pengujian inferensi, dan pengoptimalan parameter.

## Fitur Utama
1. **Large Language Models (LLMs):**  
   Penggunaan model `google/flan-ul2` untuk memahami konteks input dan menghasilkan output berbasis teks yang relevan.
   
2. **Rekayasa Prompt (Prompt Engineering):**  
   - **Metode decoding:** Greedy decoding.  
   - **Parameter panjang output:** Mengatur jumlah token minimum dan maksimum.  
   - **Stop sequences:** Menghentikan output pada pola tertentu.  

3. **Prompt Lab di Watsonx.ai:**  
   Pengujian prompt menggunakan Watson Machine Learning API, termasuk pembuatan kelas `Prompt` untuk interaksi dengan model.

4. **Inferensi Model LLM:**  
   Pengujian melibatkan evaluasi output model dengan prompt yang telah diatur, seperti analisis ulasan untuk menghasilkan poin-poin utama.

## Teknologi yang Digunakan
- **IBM Watson Machine Learning API**  
- **LLM (Large Language Model):** `google/flan-ul2`  
- **Python Libraries:**  
  - `ibm_watson_machine_learning` untuk integrasi dengan IBM Watson.  
  - Library pendukung lainnya (seperti `requests`, `json`).

## Prasyarat
1. Akun IBM Cloud aktif.
2. Watson Machine Learning instance yang sudah dikonfigurasi.
3. API Key dan Project ID dari IBM Cloud.
4. Python 3.10 atau lebih baru.

## Kesimpulan
Proyek ini berhasil menunjukkan cara kerja Large Language Models (LLMs) dengan memanfaatkan Watson Machine Learning API dan model generatif `google/flan-ul2`. Melalui pendekatan praktis dalam rekayasa prompt dan pengujian inferensi, beberapa poin utama dapat disimpulkan:
1. Efektivitas LLM untuk Berbagai Kebutuhan

   Model LLM mampu memahami input teks yang kompleks dan menghasilkan output yang relevan, menjadikannya alat yang bermanfaat untuk berbagai aplikasi, seperti analisis teks, pembuatan ringkasan, dan generasi konten.
2. Pentingnya Rekayasa Prompt
   
   Pengaturan parameter seperti metode decoding, panjang token, dan stop sequences memainkan peran penting dalam mengoptimalkan hasil yang diinginkan. Hal ini menunjukkan bahwa rekayasa prompt merupakan keterampilan esensial untuk memaksimalkan performa LLM.
3. Pemanfaatan Watson Machine Learning API
  
   Watson Machine Learning API menyediakan antarmuka yang mudah digunakan untuk menguji dan mengintegrasikan model AI generatif, mempercepat proses pengembangan aplikasi berbasis AI.

4. Peluang untuk Eksperimen dan Inovasi

   Proyek ini tidak hanya membantu memahami dasar-dasar generatif AI, tetapi juga membuka peluang untuk eksperimen lebih lanjut, seperti menguji model lain atau mengembangkan aplikasi spesifik berbasis LLM.
