familia(
    persona(
        [tomas,garcia,perez],
        fecha(7,mayo,1960),
        trabaja(profesor,60),
        alergias(fiebre_del_heno,dermatitis_atopica)
    ),
    persona(
        [ana,lopez,ruiz],
        fecha(10,marzo,1962),
        trabaja(medica,90),
        alergias(alementaria,picadura_insectos)
    ),
    [
        persona([juan,garcia,lopez],fecha(5,enero,1980),estudiante),
        persona([maria,garcia,lopez],fecha(12,abril,1992),estudiante)
    ]
).


familia(
    persona(
        [jose,perez,ruiz],
        fecha(6,marzo,1963),
        trabaja(pintor,129),
        alergias(fiebre_del_heno,dermatitis_atopica)
    ),
    persona(
        [luisa,perez,ruiz],
        fecha(12,mayo,1964),
        trabaja(medica,90),
        alergias(medicamento,alementaria)
    ),
    [
        persona([juan_luis,perez,perez],fecha(5,febrero,1990),estudiante),
        persona([maria_jose,perez,perez],fecha(12,junio,1990),estudiante),
        persona([jose_maria,perez,perez],fecha(5,julio,1990),estudiante)
    ]
).

familia(
    persona(
        [pedro,soliz,mamani],
        fecha(15,abril,1989),
        trabaja(policia,50),
        alergias(fiebre_del_heno,alimentaria)
    ),
    persona([sonia,postelo,erquicia],
            fecha(23,febrero,1995),
            estudiante
    ),
    []
).
promedioSueldo(A,B,R1,R2):-write("todos:"),
    familia(persona(_,_,trabaja(_,A),_),persona(_,_,trabaja(_,B),_),_),R1 is A+B,R2 is R1/2.


/*
mismaAlergia():-write("todos"),
    familia(persona(N,_,_,A),persona(N1,_,_,A1),_).
*/

/*
%sumar suldos
total:-write("Funciona"),nl,
    findall(G,familia(persona(_,_,trabaja(_,G)),_,_),L),
   suma(L,T),
    write("la suma total es:"),
    write(T).
suma([],0).
%suma(A,R):- length(A)<=0 R is 0
suma([L|B],R):-
    suma(B,R1),R is L+R1.
%l=60 ,B=[120,50]

%saber si pertenecea una familia como hijo
soyhijo(X):- familia(_,_,Hijos),member(X,Hijos).

mas(P):-familia(persona(P,_,trabaja(_,G)),_,_),G>60.
*/

