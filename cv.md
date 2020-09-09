## Resume

## Junior Frontend Developer

### 1. First Name, Last Name
Hello! My name is Vladislav Makeev.

### 2. Contact Info
* Email: makeevvd1@gmail.com
* Telegram: vlad_mkv

### 3. Summary
My goal is to become front-end React Javascript Developer. 

### 4. Skills
HTML, CSS, JS, React

### 5. Code examples
```javscript
export let getAuthUserData = () => (dispatch) => {
    authAPI.me()
        .then((data) => {
            if (data.resultCode === 0) {
                let {id, login, email} = data.data;
                dispatch(setUserData(id, login, email));
            }
        })
}
```

### 6. Experience

I created 2 responsive landing pages using HTML, CSS, JS, Jquery. 
I created simple social network using React Redux.
I learned React Redux, Route, Thunks, HOCs.

### 7. Education 
Finished two first chapters on learn.javscript.ru (with homework).
Finished freecodecamp.org responsive design block.
Finished 75 out of 100 lessons of "React - Way of Samurai" course: https://www.youtube.com/watch?v=gb7gMluAeao&list=PLcvhF2Wqh7DNVy1OCUpG3i5lyxyBWhGZ8

### 8. English
C1 - I am certified technical translator. Native speakers say my English is good.