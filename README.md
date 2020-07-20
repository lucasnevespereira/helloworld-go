# helloworld-go

### Notes about GO

- #### How do we run code in GO ?

  By using `go run` command.

  <i>eg:</i>
  `go run main.go` will return <i>Hi there!</i>

  Here's a list of go cli useful commands:

  - `go build` -> Compiles go code files
  - `go run` -> Compiles and executes go files.
  - `go fmt` -> Formats all the code in each go file.
  - `go install` -> Compiles and install a package.
  - `go get` -> Downloads the source code of a package.
  - `go test` -> Runs tests associated with a go project.

- #### What does package main means ?

  We can think of the word package as being like a project or a workspace.
  A package can have mutliple go files that are somehow related one to another.
  These related files all must declare in what package they are in. That's why we need to start a go file by `package < Package Name >` like `package main`.

  - Attention: there is 2 types of packages in go.

    -- Executable -> Generates a file we can run <br>
    -- Reusable -> Contains "helpers" code. Used to put reusable logic.

  - How do we now if what kind of package we are building ?

    That's actually easy. For executable package we use the name `main` so `package main`.

    <b>!Important:</b>
    Resuming to generate a executable file we need to use `package main` , otherwise we will not be able to run our files because it will be seen has an reusable package.

    And that's also the reason we need a `func main()`.

- #### What does import "fmt" means ?

* #### How is main.go organized ?
