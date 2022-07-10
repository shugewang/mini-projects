function palindrome(str) {
  str = str.toLowerCase();
  str = str.replace(/[^a-z0-9]/g, "");
  let reverse = str.split('').reverse().join('');
  console.log(str);
  console.log(reverse);
  for (let i = 0; i<str.length; i++) {
    if (str.charAt(i)!=reverse.charAt(i)){
      return false;
    }
  }
  return true;
}
