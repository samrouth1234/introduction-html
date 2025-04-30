
1, What is css ? Cascading Style Sheet​​ ។
2, How to use css ? សម្រាប់ដាក់ Style អោយ Web Page ។
3, Syntax css 
4, Selector in CSS  មាន 3 របៀប 
    - select ដោយប្រើឈ្មោះ Tag មានដូចជា​ h1 , p , span , a , ...​​ ។
    - select ដោយការដាក់ ID (លេខសម្គាល់)​ អោយ Tag​​ ។
    - select ដោយការដាក់ឈ្មោះអោយ Tag​ ដោយប្រើ property មួយឈ្មោះថា class ។
5, Command
6, របៀបដាក់ Color អោយ Tag 
7, របៀបដាក់ Background អោយ Tag
8, របៀបដាក់ Border អោយ Tag

9, របៀបដាក់ Pending អោយ Tag
10, របៀបដាក់ Margin អោយ Tag 
11, របៀបដាក់ Width និង Height
12, សិក្សាអំពើ Box Model

របៀបដាក់ style អោយ HTML មានបីគឺ external css , internal css , inline css ។
•  Inline css គឺជាការដាក់style នៅក្នុងTag ដោយប្រើ property មួយឈ្មោះថា style 
Example : <h1 style=”color:red”> Hello </h1>
•  External css គឺជាការសរសេរ style css នៅក្នុង File ដាច់ដោយឡែក។ ប្រសិនបើយើងចង់ ហៅ style នោះមកប្រើយើងត្រូវតែខលហៅ File Css មកដោយគ្រាន់តែដាក់ក្នុង Heade Tage ។ Example : <head> <link rel=”stylesheet” href=”style.css”/> </head>
•  Internal css គឺជាការសេរសេរ Style សិ្តតនៅក្នុង Tag Style ។
Example : <head> <style> selectors { color : red ;} </style> </head>
Selectors គឺជាការជ្រើសរើសយក Tag មកយកដាក់ Style ។
Selectors នៅក្នុង CSS មាន 3 គឺ Id , Class , TageName ។
•  ID
o  ប្រើសញ្ញា #  ។ Example : #para1 { text-align: center; color: red }
•  Class
o  ប្រើសញ្ញា  .។ Example : .para1 { text-align: center; color: red }
•  TageName
o  ប្រើឈ្មោះ Tag ដូចជា h1 , p , a , li , table … ។