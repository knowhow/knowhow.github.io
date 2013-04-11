sadrzaj sa posterous.com do-we-know-how.bring.out.ba

## build site


instaliraj grunt-bake sa github/hernad, napravi `posts.orig` direktorij, pokreni grunt taskove, kopiraj rezultat u `posts`:

    npm install
    cp -av posts posts.orig
    grunt
    cp -av dest/dest1/posts.orig/* posts/


