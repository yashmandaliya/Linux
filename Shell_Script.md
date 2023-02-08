# 1) Shell Scrit :- Hello World
```
echo "Hello World" 

```
## Output:-
![Hello](https://user-images.githubusercontent.com/112624754/217421559-17fb46a2-a896-477c-9a7f-26b3c63a6634.png)

# 2) Shell Scrit :- While Loop
```
#!\bin\bash
i=1
while [ $i -le 20 ]
do
    echo $i
    i=$(($i+1))
done
```
## Output:-
![While2](https://user-images.githubusercontent.com/112624754/217423933-3cf315a9-b146-4a9c-a505-6e3d3b8394d4.png)


# 3) Shell Scrit :- For Loop
```
#!\bin\bash
for((i=10;i>0;i--))
do
	echo -n " $i"
done
printf "\n"
```
## Output:-
![For2](https://user-images.githubusercontent.com/112624754/217424008-d28e7539-a94b-44f0-999c-36d7a4219b98.png)


# 4) Shell Scrit :- Get User Input 
```
#!\bin\bash
echo "Ener Name"
read name
echo "Welcome !! $name to JavaTPoint"
```
## Output:-
![Get](https://user-images.githubusercontent.com/112624754/217423988-ea0aa8b9-61ff-496b-913a-42831d0f92fc.png)


# 5) Shell Scrit :- If Else Statment
```
#!\bin\bash
echo "Enter Value"
read n
if [$n -lt10]
then 
	echo "It Is A One Digit Number"
else 
	echo "It Is A Two Digit Number"
fi

```
## Output:-
![if](https://user-images.githubusercontent.com/112624754/217424044-81436891-710d-4e0e-affd-6cbbc25f2121.png)


# 6) Shell Scrit :- Command Line Argument
```
#!\bin\bash
echo "Total Arguments : $#"
echo "First Argument = $1"
echo "Second Argument = $2"
```
## Output:-

![Command](https://user-images.githubusercontent.com/112624754/217424083-d65c53b5-518a-49ef-82ce-4daa756783a5.png)

