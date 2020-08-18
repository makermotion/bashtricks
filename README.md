## bashtricks

#### To create multiple folders with some order.(e.g. foo1 foo2 foo3 .... foo9 ||  fooA, fooB, fooC)  / tr: Sıralı klasörler oluışturmak için (örn. foo1 foo2 foo3 .... foo9 ||  fooA, fooB, fooC)
You can replace the "x" whatever you want. / "x" i yaratmak istediğiniz dosya isim formatına göre değiştirebilirsiniz.

```bash
mkdir foo{<<x>>...<<x>>}
```
![output](https://user-images.githubusercontent.com/22776403/90341531-0287c080-e009-11ea-813d-71471ee4558d.gif)
***
#### To check differences between folders / tr: Klasörler arasındaki farkları kontrol etmek için
a and b here is the things that you want to compare. (e.g. folders, files ..) / tr: a ve b 'yi karşılaştımak istedğiniz şeylere göre değiştirebilirsiniz. (ör: klasör, dosya ..)

```bash
diff <<a>> <<b>>
```
![output_diff](https://user-images.githubusercontent.com/22776403/90341732-9908b180-e00a-11ea-9e24-57a2a376348a.gif)
***
#### To fetch a summary manual for bash commands / tr: bash komutları için özet şeklinde bir kullanım klavuzu
"x" here is the bash command that you want to see the summary manual of. (e.g. ls, tar etc.) / tr: "x" burada özet kullanım klavuzunu görmek istediğiniz bash komutu. (ör: ls, tar ..)

```bash
tldr <<x>>
```
![output_tldr](https://user-images.githubusercontent.com/22776403/90552068-f0d62280-e19a-11ea-9454-051dc67e23fc.gif)
