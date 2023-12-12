# Just a `h1` tag

```
app = FastAPI()
init_db()
app.mount("/static", StaticFiles(directory="static"), name="static")

templates = Jinja2Templates(directory="templates")
```

![An Image of a yakto cat](https://octodex.github.com/images/yaktocat.png)
