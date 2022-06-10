https://github.com/littlejohn19/TAW-kol-2


## Zadanie

Stworzenie serwisu pobierającego dane z serwera (XY-data - gdzie XY to inicjały)

Do pobrania danych został przygotowany serwer: https://taw-posts.herokuapp.com/


    Posiada on dostępne 2 ścieżki do pobrania danych:

    GET /api/posts
    GET /api/posts/:id (id z przedziału <1,3>)

    Wygenerowany serwis powinien posiadać 2 metody:

pobierająca wszystkie wpisy na blogu,
pobierające pojedynczy wpis na blogu

Zadanie

Stworzenie 3 komponentów (każdy z przyrostkiem XY - gdzie XY to inicjały):

posts-XY
posts-item-XY
posts-details-XY

    Pierwszy komponent powinien za pomocą utworzonego serwisu pobierać wszystkie elementy z serwera 
    i wyświetlać je przy użyciu dyrektywy *ngFor.
    Za wyświetlanie pojedynczego elementu odpowiedzialny jest drugi komponent, 
    który powinien wyświetlać wszystkie otrzymane dane z serwera w pojedynczym obiekcie. 
    Informacje powinny być przekazane za pomocą mechanizmu @Input.


