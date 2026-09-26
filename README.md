<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Student Registration Form</title>

    <style>

        body {
            background-color: #ffe4e1;
            font-family: "Times New Roman", serif;
        }

        .container {
            width: 650px;
            margin: 30px auto;
        }

        h1 {
            text-align: center;
            font-size: 28px;
            margin-bottom: 30px;
        }

        table {
            width: 100%;
            border-spacing: 8px;
        }

        td:first-child {
            width: 170px;
        }

        input[type="text"],
        input[type="email"],
        input[type="password"],
        input[type="tel"] {
            width: 200px;
            height: 17px;
        }

        .roll {
            width: 200px !important;
        }

        .small {
            width: 55px !important;
        }

        .name {
            width: 90px !important;
        }

        select {
            width: 230px;
            height: 22px;
        }

        textarea {
            width: 195px;
            height: 65px;
            resize: none;
        }

        input[type="file"] {
            width: 230px;
        }

        input[type="checkbox"],
        input[type="radio"] {
            margin-right: 3px;
        }

        .date-note {
            font-style: italic;
        }

        .register {
            text-align: center;
        }

        button {
            font-size: 10px;
            padding: 2px 6px;
        }

    </style>
</head>

<body>

<div class="container">

    <h1>Student Registration Form</h1>

    <form>

        <table>

            <!-- Roll Number -->
            <tr>
                <td>Roll no. :</td>
                <td>
                    <input type="text" class="roll">
                </td>
            </tr>

            <!-- Student Name -->
            <tr>
                <td>Student name :</td>
                <td>
                    <input type="text" class="name" placeholder="First Name">
                    -
                    <input type="text" class="name" placeholder="Last Name">
                </td>
            </tr>

            <!-- Father's Name -->
            <tr>
                <td>Father's name :</td>
                <td>
                    <input type="text">
                </td>
            </tr>

            <!-- Date of Birth -->
            <tr>
                <td>Date of birth :</td>
                <td>
                    <input type="text" class="small" placeholder="Day">
                    -
                    <input type="text" class="small" placeholder="Month">
                    -
                    <input type="text" class="small" placeholder="Year">

                    <span class="date-note">
                        (DD-MM-YYYY)
                    </span>
                </td>
            </tr>

            <!-- Mobile -->
            <tr>
                <td>Mobile no. :</td>
                <td>
                    <input type="text"
                           value="+91"
                           style="width: 35px;">
                    -
                    <input type="text">
                </td>
            </tr>

            <!-- Email -->
            <tr>
                <td>Email id :</td>
                <td>
                    <input type="email">
                </td>
            </tr>

            <!-- Password -->
            <tr>
                <td>Password :</td>
                <td>
                    <input type="password">
                </td>
            </tr>

            <!-- Gender -->
            <tr>
                <td>Gender :</td>
                <td>
                    <input type="radio" name="gender">
                    Male

                    <input type="radio" name="gender">
                    Female
                </td>
            </tr>

            <!-- Department -->
            <tr>
                <td>Department :</td>
                <td>

                    <input type="checkbox">
                    CSE

                    <input type="checkbox">
                    IT

                    <input type="checkbox">
                    ECE

                    <input type="checkbox">
                    Civil

                    <input type="checkbox">
                    Mech

                </td>
            </tr>

            <!-- Course -->
            <tr>
                <td>Course :</td>
                <td>
                    <select>
                        <option>
                            ---------------- Select Current Course's ----------------
                        </option>

                        <option>
                            Web Development
                        </option>

                        <option>
                            Computer Science
                        </option>

                        <option>
                            Information Technology
                        </option>

                        <option>
                            Software Engineering
                        </option>
                    </select>
                </td>
            </tr>

            <!-- Student Photo -->
            <tr>
                <td>Student photo :</td>
                <td>
                    <input type="file">
                </td>
            </tr>

            <!-- City -->
            <tr>
                <td>City :</td>
                <td>
                    <input type="text">
                </td>
            </tr>

            <!-- Address -->
            <tr>
                <td>Address :</td>
                <td>
                    <textarea></textarea>
                </td>
            </tr>

        </table>

        <div class="register">
            <button type="submit">Register</button>
        </div>

    </form>

</div>

</body>
</html>
