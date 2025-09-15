# bookbot

TR: Romanları analiz eden ve içinde bulunan kelime ve karakter kullanımına ilişkin istatistiksel bir rapor yazdıran bir Python programı. Bilgisayarınızda python3'ün kurulu olması gerekli. Daha sonra proje klasörünü vscode ile açıp terminalden ```python3 main.py kitapadi.txt``` yazarak kullanabilirsiniz. Kitap içeriğinin txt dosyası içerisinde olması gerek. Analiz ettirmek istediğiniz kitabın txt haline burdan ulaşabilirsiniz: https://www.gutenberg.org/ Plain Text UTF-8 formatına tıklayıp tüm sayfayı kopyalayıp books klasörünün içine bir txt dosyası oluşturup onun içine yapıştırmalısınız. Daha sonra o txt dosyasının adı kitap adı olur. path=books/kitapadi.txt

EN: A Python program that analyzes novels and prints a statistical report of the word and character usage found within. You have to install python3 on your computer. Then, you can open the project folder with vscode and use it by typing ```python3 main.py bookname.txt``` in the terminal. Book must be in a txt file. You can access the txt version of the book you want to analyze from here:  https://www.gutenberg.org/ You should click: 	Plain Text UTF-8 format then copy all of the page and paste it in a txt file inside books folder. That txt file's name will be the book's name. path=books/bookname.txt




============ BOOKBOT ============

----------- Word Count ----------

--------- Character Count -------

Kullanım/Usage: python3 main.py <path_to_book>

Örnek/Example: 
```
python3 main.py books/frankenstein.txt
```