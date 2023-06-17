Name:-Marapureddy Siva Rohith Reddy
Theory questions
1) Mention the working of Internet Website in Terms of Front-end & Back-end Divisions
Ans) Front end:-
         1.It is interaction between user and server.
         2.When user sends  requests to server.
          3.Server give its response in form of webpage.
          4.Interaction between user and webpage occurs via browser.
         5.For example if user types www.google.com in browser server receives it         
            and sends  google webpage as response.
         6.We use HTML,CSS,Javascript to create front page.
        Back end:-
         1.It is interaction between server and database.
         2.When server search in database for data.
         3.Database give required data which is called fetching data from database.
          4.We use SQL,MongoDB,React e.t.c to create backend software.
2) What are tags in HTML? Explain the each category of tag with an Example.
Ans)Tags:-
                Tags are keywords surrounded by angle brackets like <html>.
         These are structures of HTML .Some of their categories are:-
     1. Heading Tags:
Heading tags define headings or titles on a web page. They range from h1 to h6 with h1 being the highest level and <h6> the lowest. 
Example:""<h1> HELLO WORLD </h1>""  prints hello world as heading



2 )Paragraph Tags:-
Paragraph tags define paragraphs of text. They are represented by the <p> tag. Example:-<p> This is para </p>
3) Image Tags:
Image tags display images on a web page. They are represented by the <img> tag and require a "src" attribute specifying the image URL. 
Example: <img src=image.png alt=”not available”> it paste applied imager and image is not present then alt will show
4)List Tags:
List tags are used to create ordered and unordered lists. <ul> represents an unordered list (bulleted), and <ol> represents an ordered list (numbered). Example: <ul>
  <li>Idly</li>
  <li>Vada</li>
  <li>Sambar</li>
</ul>, prints above list in bullet form.<br>
5)Table Tags:
Table tags are used to create tables on a web page. They consist of the table tag for the table itself, tr for table rows, th for table headers, and td for table data. 
Example: <table>
  <tr>
    <th>Name</th>
    <th>Designation</th>
  </tr>
  <tr>
    <td>Rohith</td>
    <td>Student</td>
  </tr>
</table>
<br>
3) Explain the working Procedure of Virtual DOM.
Ans)1. The Virtual DOM (VDOM) is a concept used in web development frameworks like React to improve performance and optimize updates to the user interface.<br>
2.When you create a user interface in React or a similar framework, the initial render creates a virtual representation of the UI known as the Virtual DOM. It's a lightweight copy of the actual DOM.<br>
3.Once the Virtual DOM is created, it needs to be rendered onto the actual browser DOM so that it can be displayed to the user. This initial rendering creates the actual HTML elements and inserts them into the DOM.<br>
4. The Virtual DOM is a tree-like structure composed of virtual elements, which are JavaScript objects representing the HTML elements. Each virtual element corresponds to a real DOM element.<br>      
 4) Mention some Differences between MySQL and No SQL<br>
Ans)MySQL:-<br>
1.	It follows a structured, tabular data model with predefined schemas and fixed tables. It uses SQL (Structured Query Language) for defining and manipulating the data.<br>
2.	It typically scales vertically, meaning it requires more powerful hardware or a larger server to handle increased loads.<br>
3.	It requires a predefined schema, meaning the structure of the data must be defined before storing it. Modifying the schema can be challenging and may require altering existing data.<br>
4.	It provides ACID (Atomicity, Consistency, Isolation, Durability) properties, ensuring data consistency and integrity. It supports transactions that guarantee all or nothing operations.<br>
NOSQL:-<br>
1.	It employs a flexible, schema-less data model. There are various types of NoSQL databases, including document-oriented, key-value, columnar, and graph databases.<br>
2.	NoSQL databases are designed to scale horizontally, which means they can distribute data across multiple servers, making them highly scalable and able to handle large amounts of data and traffic.<br>
3.	It offers more flexibility in terms of schema evolution. It allows for dynamic and flexible schema changes, making it easier to adapt to evolving application requirements.<br>
4.	NoSQL databases may have varying levels of support for ACID transactions. Some NoSQL databases prioritize scalability over strict transactional guarantees, providing eventual consistency instead.<br>

5) Explain any one DBMS Technology in your own words<br>
Ans) One of DBMS technology is MongoDB<br>
1.	MongoDB is a document-oriented NoSQL database that provides a flexible and scalable solution for managing and storing data.<br>
2.	In MongoDB, data is organized and stored as documents, which are similar to JSON objects<br>
3.	MongoDB allows for dynamic and flexible schemas, meaning each document within a collection can have its own unique structure.<br>
4.	MongoDB is designed to scale horizontally, allowing for distributing data across multiple servers or clusters.<br>
5.	MongoDB provides a powerful and expressive query language for retrieving and manipulating data.










