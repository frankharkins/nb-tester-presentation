### Notebooks and how we test them

---

## In this presentation

* What a Jupyter notebook is <!-- .element: class="fragment" data-fragment-index="1" -->
* Some features and quirks of notebooks <!-- .element: class="fragment" data-fragment-index="2" -->
* How to manipulate them programmatically <!-- .element: class="fragment" data-fragment-index="3" -->
* (Next time) How we test them with nb-tester <!-- .element: class="fragment" data-fragment-index="4" -->

---

## What is a Jupyter notebook?

* Originated in IPython <!-- .element: class="fragment" data-fragment-index="1" -->
  * Interactive REPL (read evaluate print loop) <!-- .element: class="fragment" data-fragment-index="2" -->
* Jupyter is an IPython REPL... <!-- .element: class="fragment" data-fragment-index="3" --> **in a browser!** <!-- .element: class="fragment" data-fragment-index="4" -->
  * Easier to use <!-- .element: class="fragment" data-fragment-index="5" -->
  * Rich outputs <!-- .element: class="fragment" data-fragment-index="6" -->

[Demo time]() <!-- .element: class="fragment" data-fragment-index="7" -->

---

## The notebook file format

* .ipynb extension <!-- .element: class="fragment" data-fragment-index="1" -->
* JSON files containing: <!-- .element: class="fragment" data-fragment-index="2" -->
  * List of cells <!-- .element: class="fragment" data-fragment-index="2" -->
  * Some metadata <!-- .element: class="fragment" data-fragment-index="2" -->

---

## Notebook source code example

```json [0|2-36|3-12|4|5|6|7-11|13-35|18-31|21-23|24-28|37-57|55-56|0]
{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "70662ad0-6ebd-447e-9eac-e73fb1f29d60",
   "metadata": {},
   "source": [
    "# Quirks of Jupyter notebooks\n",
    "\n",
    "This notebook demonstrates some behaviours..."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "id": "83580785-405a-4eb8-b6ac-777b5aedea85",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "Circle(color='red')"
      ],
      "image/svg+xml": [
       "<svg version=\"1.1\" width=\"300\" height=\"200\" xmlns=\"http://www.w3.org/2000/svg\">\n",
       "  <circle cx=\"150\" cy=\"100\" r=\"80\" fill=\"red\" />\n",
       "</svg>\n"
      ]
     }
    }
   ],
   "source": [
    "..."
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.1"
  },
  "title": "Example notebook",
  "description": "SEO description, must be 50-160 characters"
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
```

---

Thank you!
