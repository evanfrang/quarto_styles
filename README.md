# Project Title Here
Evan Frangipane

## 🧠 Goal

Briefly describe what this project does, what problem it solves, or what
makes it interesting.

> **Live Demo**
>
> This project is hosted at [example.com](https://example.com). It may
> take a moment to wake up if hosted on a free tier.

------------------------------------------------------------------------

## 📊 Dataset

-   Source: [Link to dataset](#)
-   Description: What’s in it?
-   Preprocessing: What did you do to it?

<img src="images/moon.jpg" data-fig-align="center" />

------------------------------------------------------------------------

## 🧪 Results

### 🔹 Logistic Regression

<table>
<thead>
<tr>
<th>Class</th>
<th>Precision</th>
<th>Recall</th>
<th>F1-Score</th>
<th>Support</th>
</tr>
</thead>
<tbody>
<tr>
<td>astro</td>
<td>0.95</td>
<td>0.93</td>
<td>0.94</td>
<td>3531</td>
</tr>
<tr>
<td>cond_matter</td>
<td>0.87</td>
<td>0.88</td>
<td>0.87</td>
<td>3435</td>
</tr>
<tr>
<td>…</td>
<td>…</td>
<td>…</td>
<td>…</td>
<td>…</td>
</tr>
</tbody>
</table>

\*\* Table 1. Log Reg caption \*\*

<img src="images/moon.jpg" data-fig-align="center" />

### 🔹 DistilBERT

-   Training time: ~6 hours
-   Performance: slightly better, slower inference

------------------------------------------------------------------------

## 🔚 Conclusion

Summarize your takeaways. Is the model good enough? What could be
improved?

------------------------------------------------------------------------

## 🚀 Usage

``` bash
# install requirements
pip install -r requirements.txt

# run model locally
python app.py
```

------------------------------------------------------------------------

## 📝 Notes

This README is generated via [Quarto](https://quarto.org). To rebuild:

``` bash
quarto render arxiv.qmd --to gfm
```

Or set up your project so this is automatic.
