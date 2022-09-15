# Taras Kvachan

***

## Contact information

- **Phone**: +38 098 583 72 44
- **Email**: taras.kvachan@gmail.com
- **Telegram**: @seo-guild
- **Location**: Kyiv, Ukraine

## About Me

SEO specialist with 7 years of commercial experience with a focus on on-page optimization. Have an experience of managing projects and teams.

## Skills

- HTML5, CSS3
- JS
- Git
- Figma

## Code example

    //Given an array of integers , Find the minimum sum which is obtained from summing each Two integers product.

    function minSum(arr) {
        let sum = 0;
        arr = arr.sort((a, b) => a - b);
        for (let i = 0; i < arr.length / 2; i++) {
            sum += arr[i] * arr[arr.length - 1 - i]
        }
        return sum;
    }

## Education

Kharkiv National University of Radio Electronics, Information Control System and Technologies