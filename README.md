**Flask Application Design**

**Problem:** Building a website to teach Hindi

**HTML Files:**

* **index.html**: Main page of the website, providing an interface for learning Hindi.
* **lessons.html**: A dynamic page that lists all the Hindi lessons, with links to each lesson.
* **lesson.html**: A dynamic page that displays a specific Hindi lesson, including grammar, vocabulary, and exercises.

**Routes:**

* **@app.route('/')**: Route for the main page (index.html).
* **@app.route('/lessons')**: Route for the lessons page (lessons.html).
* **@app.route('/lesson/<lesson_id>')**: Route for a specific lesson page (lesson.html), where `<lesson_id>` is a parameter representing the ID of the lesson.
* **@app.route('/exercise/<exercise_id>')**: Route for a specific exercise page, where `<exercise_id>` is a parameter representing the ID of the exercise.
* **@app.route('/api/lessons')**: API endpoint to retrieve a list of all lessons.
* **@app.route('/api/lesson/<lesson_id>')**: API endpoint to retrieve data for a specific lesson.
* **@app.route('/api/exercise/<exercise_id>')**: API endpoint to retrieve data for a specific exercise.