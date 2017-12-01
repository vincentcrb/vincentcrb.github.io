# CV VINCENT CARABIN

Petit CV bien sympa en HTMl / CSS. 

## Différentes parties de mon site

### Float

J'ai placé un petit float sur le menu pour le potentiel logo de la personne. Ici j'ai juste marqué mon nom.


```
<div class="logo">
	<h3><a href="#">Vincent Carabin</a></h3>
</div>

.logo{
	float: left;
	margin: 0px 15px;
}

```

### Display flex

La partie compétence ainsi que le portfolio sont en display flex.


```
 <div class="projet_container">
 	<div class="projet">
 		<a href="">
 		<div class="img_prev"></div>
 		<h3>Projet 1</h3>
 		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed eu tempus odio, et condimentum neque.</p>
 		</a>
 	</div>
 </div>
```


### Animation CSS

Petite animation sur les éléments du menu ainsi que le bouton contact. "Progress bar" sur la compétence HTML dans la partie compétence à l'aide d'un @keyframes


```
.barre_html:hover{
	-webkit-animation: myprogress 3s;
    animation: myprogress 3s;
}
@keyframes myprogress {
   0% {width: 0%;}
   100% {width: 90%;}
}
```

### Parallax

J'ai fait un petit parallax car pourquoi pas.

### Media queries

Un peu de responsive design, même si je ne l'ai pas rendu 100% responsive je me suis occupé des plus gros blocs comme le bloc container.


