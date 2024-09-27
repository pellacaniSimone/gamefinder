# Install instructions

---

To install all the project libraries, run the following command:
```
pip install -r requirements.txt
```

The user interface was created using the Django framework.  
To test it, enter the `/GameSearcher` folder and run the following command:
```
python manage.py runserver
```
Then go to http://127.0.0.1:8000/

**Benchmark:**
The file containing the UIN is located in `UIN.txt`.  
In the `Data_comparison` file, you will find the benchmark evaluations.  
The following metrics were used for the benchmark evaluation:
- precision and recall
- average precision
- MAP
- DCG
- Harmonic mean of DCG