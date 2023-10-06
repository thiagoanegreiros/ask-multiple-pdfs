
source venv/bin/activate       
pip install -r requirements.txt

#verify if this is working
python -c "from huggingface_hub import model_info; print(model_info('gpt2'))"
streamlit run app.py
