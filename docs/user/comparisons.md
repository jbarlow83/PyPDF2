# PyPDF2 vs X

PyPDF2 is a [free] and open source pure-python PDF library capable of
splitting, merging, cropping, and transforming the pages of PDF files.
It can also add custom data, viewing options, and passwords to PDF
files. PyPDF2 retrieve metadata from PDFs.

A core feature of PyPDF2 is that it's pure Python. That means there is
no C dependency. It has been used for over 10 years and for this reason
a lot of support via StackOverflow and examples on the internet.

## pikepdf

[pikepdf] is a Python binding to [QPDF], a well regarded C++ library
for inspecting and correcting PDFs. pikepdf and PyPDF2 have feature 
sets that don't exactly - some tasks are easier in, some are easier in 
the other.

pikepdf provides binary wheels for all common platforms to ease 
installation; however, users of less common platforms or those with 
security concerns about binary wheels may need  to compile the library 
from source. pikepdf is licensed under MPL2.

## PyMuPDF

[PyMuPDF] is a Python binding to [MuPDF]. PyMuPDF is a powerful and
feature-rich PDF library - one of the most capable open source PDF
libraries. PyMuPDF also provides binary wheels, with the same drawbacks
as mentioned for pikepdf.

However, MuPDF is licensed under the highly restrictive AGPLv3 license; 
some users may need to consider a commercial license unless they intend 
to release their software under AGPLv3 as well.

## pyPDF

PyPDF2 was forked from pyPDF. pyPDF has been unmaintained for a long
time.

## PyPDF3 and PyPDF4

Developing and maintaining open source software is extremely
time-intensive and in the case of PyPDF2 not paid at all. Having a
continuous support is hard.

PyPDF2 was initially released in 2012 on PyPI and received releases
until 2016. From 2016 to 2022 there was no update - but people were
still using it.

As PyPDF2 is free software, there were attempts to fork it and continue
the development. PyPDF3 was first released in 2018 and still receives
updates. PyPDF4 has only one release from 2018.

I, Martin Thoma, the current maintainer of PyPDF2, hope that we can
bring the community back to one path of development. Let's see.

  [free]: https://en.wikipedia.org/wiki/Free_software
  [PyMuPDF]: https://pypi.org/project/PyMuPDF/
  [MuPDF]: https://mupdf.com/
  [pikepdf]: https://pypi.org/project/pikepdf/
  [QPDF]: https://github.com/qpdf/qpdf

## pdfminer.six

[`pdfminer.six`](https://pypi.org/project/pdfminer.six/) is a PDF library
focused on text extraction and reconstruction. It is capable of extracting
text from PDFs along with positional information. pdfminer.six is focused
on this task and does not generate or modify PDFs.

Please be aware that there is also
[`pdfminer`](https://pypi.org/project/pdfminer/) which is not maintained.

## Others

* [`pdfrw`](https://pypi.org/project/pdfrw/)
* [`pdfrw2`](https://pypi.org/project/pdfrw2/)
* [`pyfpdf`](https://github.com/reingart/pyfpdf)
