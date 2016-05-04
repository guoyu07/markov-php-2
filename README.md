# markov-php

Simple markov chain implementation for PHP.

## Example usage
<pre>
<?php
include("Markov.class.php");
$chain = new Markov;

$chain->train("This is a test, a very simple test that we can use to do things.");
$chain->train("Another test is this.");
$chain->train("Maybe we should keep it simple.");

echo $chain->generateText(5);
</pre>

