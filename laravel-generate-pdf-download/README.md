## Step 1 - Install Laravel 
<code> composer create-project laravel/laravel laravel-generatepdf or laravel new laravel-generatepdf </code>

## Step 2 - Install DomPDF Package
<code> composer require barryvdh/laravel-dompdf </code>

## Step 3 - Create a Controller
<code> php artisan make:controller GeneratePDFController </code>

## Step 4 - Insert Fake Data in User table
<code> php artisan tinker </code>
<br>
<code> User::factory()->count(10)->create() </code>

## Step 5 - Add Route

## Step 6 - Create View file

## Output:-

![image](https://user-images.githubusercontent.com/90952992/209433021-375a8634-53b3-4e95-8ee3-68900f6f8952.png)
