# question_two
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>question two</title>
  <script language="javascript">

      /*Question 2: Fibonacci Sequence
  Write a program to generate the Fibonacci sequence up to 100.*/
  
    function Sequence(limit) {
      limit=prompt('enter the limit');
    let z = [0, 1];
    let i = 2;
    while (z[i - 1] + z[i - 2] <= limit) {
        z[i] = z[i - 1] + z[i - 2];
        i++;
    }
    document.write(z);
    return z;
}


  </script>
</head>
<body>
 <button onclick="Sequence()">calculate</button>
</body>
</html>
