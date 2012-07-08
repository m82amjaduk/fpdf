## FPDF Bundle for Laravel, by Mark van der Putten

## How to install ##

In application/bundles.php add:

```php
'fpdf' => array('auto' => true),
```

## Basic example ##

Here is a basic example on how to use the bundle:

```php
$pdf = new Fpdf();
$pdf->AddPage();
$pdf->SetFont('Arial','B',16);
$pdf->Cell(40,10,'Hello World!');
$pdf->Output();
```

## FPDF ##

FPDF is a PHP class which allows to generate PDF files with pure PHP, that is to say without using the PDFlib library. F from FPDF stands for Free: you may use it for any kind of usage and modify it to suit your needs.

- Homepage:      http://www.fpdf.org/

On the fpdf homepage you will find links to the documenation, forums and so on.