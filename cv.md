# Alina Rozhkova

## Junior Frontend Developer

![cv-photo](/rsschool-cv/images/photo_2024-10-30_12-03-33.jpg)

### __Contact information:__

- __Location:__ Minsk, Belarus
- __E-mail:__ <lnrzhkv3367337@gmail.com>
- __Discord:__ lnrzhkv
- __Phone:__ +375 33 336-73-37
- [__Telegram__](https://t.me/ln_rzhkv)
- [__GitHub__](https://github.com/lnrzhkv)

### __Some info about me:__

I am an aspiring front-end developer with a strong desire to learn and grow in the field of web development.

My journey began with a fascination for how websites come alive, and I have since honed my skills in __HTML, CSS/SCSS, and JavaScript__. As well as I have experience working on academic projects.

I strive to achieve one goal: *creating foolproof and dynamic user interfaces*.

I enjoy *working in a team* where I can share my ideas and I appreciate *constructive feedback* as a tool for growth.

### __Skills:__

- HTML
- CSS/SCSS
- JavaScript (Basic)
- Git, GitHub

### __Code example:__

__Fix string case 7 kyu KATA from CODEWARS:__ *given a string that may have mixed uppercase and lowercase letters and your task is to convert that string to either lowercase only or uppercase only.*

```function solve(s) {
    let lowerCount = 0;
    let upperCount = 0;
  
    for (let symbol of s) {
      if(symbol === symbol.toLowerCase()) {
        lowerCount++;
      } 
      else {
        upperCount++;
      }
    }
  
    if(lowerCount >= upperCount) {
      return s.toLowerCase();
  }
    else {
      return s.toUpperCase(); 
  }
}
```
