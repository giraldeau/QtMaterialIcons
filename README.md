# QtMaterialIcons
Material Design Icons binding for Qt

Let's say you are looking for an icon to use in your Qt application. You want something depicting an `eye` and you found it in the  [Material Design Icons](http://materialdesignicons.com/) collection:

![Eye icon from Material Design Icons](https://i.imgur.com/5XqfpdV.png)

With this library, you can easily use it by just calling
```cpp
material::pixmap("eye");
```

And with a few more lines:
```cpp
auto label = new QLabel;
label->setPixmap(material::pixmap("eye", QSize(32, 32), Qt::darkGray));

label->show();
```

You got this:  
![Resulting Pixmap in a Window](https://i.imgur.com/hZ84uFS.png)

# How to?

1) Include header and source files into your build process
2) Include resources (Qt resource file and the font file) into your build process
3) Start using it.

# License
Code - MIT 

Templates - WTFPL

Community Icons - SIL Open Font License 1.1

Google Material Design Icons - Apache License 2.0
