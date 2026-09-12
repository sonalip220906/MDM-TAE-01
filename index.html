<!DOCTYPE html>
<html>
<head>
    <title>Student Attendance Tracker</title>

    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="min-h-screen bg-[#101516]">

    <div class="max-w-3xl mx-auto p-6">

        <!-- Heading -->
        <div class="bg-gradient-to-r from-teal-900 via-gray-900 to-teal-900 rounded-xl shadow-lg p-6 text-center mb-6">

            <h1 class="text-3xl font-bold text-white">
                Student Attendance Tracker
            </h1>

            <p class="text-white">
                Digital Classroom Attendance Manager
            </p>

        </div>


        <!-- Add Student -->
        <div class="bg-gradient-to-r from-teal-600 via-gray-900 to-teal-600 rounded-xl shadow-lg p-6 mb-6">

            <h2 class="text-xl font-bold text-white mb-4">
                Add Student
            </h2>

            <label class="font-semibold text-white">USN</label>

            <input type="text" id="usn"
                placeholder="Enter USN"
                class="w-full p-3 border rounded-lg mb-4">


            <label class="font-semibold text-white">Student Name</label>

            <input type="text" id="name"
                placeholder="Enter Student Name"
                class="w-full p-3 border rounded-lg mb-4">


            <button type="button" onclick="addStudent()"
                class="w-full bg-gray-900 text-white p-3 rounded-lg font-bold hover:bg-green-700">

                Add Student

            </button>

        </div>


        <!-- Attendance -->
        <div class="grid grid-cols-3 gap-4 mb-6">

            <div class="bg-white p-4 rounded-xl shadow text-center">
                <p>Total</p>
                <h2 id="total" class="text-2xl font-bold text-blue-600">0</h2>
            </div>

            <div class="bg-green-100 p-4 rounded-xl shadow text-center">
                <p>Present</p>
                <h2 id="present" class="text-2xl font-bold text-green-600">0</h2>
            </div>

            <div class="bg-red-100 p-4 rounded-xl shadow text-center">
                <p>Absent</p>
                <h2 id="absent" class="text-2xl font-bold text-red-600">0</h2>
            </div>

        </div>


        <!-- Student List -->
        <div class="bg-gradient-to-r from-teal-600 via-gray-900 to-teal-600 rounded-xl shadow-lg p-6">

            <h2 class="text-xl font-bold text-white mb-4">
                Student List
            </h2>

            <div id="studentList"></div>

        </div>

    </div>


    <script>

        let total = 0;
        let present = 0;


        function addStudent() {

            let usn = document.getElementById("usn").value;
            let name = document.getElementById("name").value;


            if (usn === "" || name === "") {

                alert("Please enter USN and Student Name");

                return;
            }


            total++;


            let studentList =
                document.getElementById("studentList");


            let student = document.createElement("div");


            student.className =
                "flex justify-between items-center bg-gray-100 p-4 rounded-lg mb-3";


            student.innerHTML =
                "<div>" +
                "<p class='font-bold text-gray-900'>" +
                usn +
                "</p>" +
                "<p class='font-semibold'>" +
                name +
                "</p>" +
                "</div>" +

                "<button type='button' " +
                "onclick='markPresent(this)' " +
                "class='bg-red-500 text-white px-4 py-2 rounded-lg'>" +
                "Absent" +
                "</button>";


            studentList.appendChild(student);


            document.getElementById("usn").value = "";
            document.getElementById("name").value = "";


            updateCount();
        }


        function markPresent(button) {

            if (button.innerHTML === "Absent") {

                button.innerHTML = "Present";

                button.className =
                    "bg-green-500 text-white px-4 py-2 rounded-lg";

                present++;

            }
            else {

                button.innerHTML = "Absent";

                button.className =
                    "bg-red-500 text-white px-4 py-2 rounded-lg";

                present--;

            }

            updateCount();
        }


        function updateCount() {

            document.getElementById("total").innerHTML = total;

            document.getElementById("present").innerHTML = present;

            document.getElementById("absent").innerHTML =
                total - present;
        }

    </script>

</body>
</html>
