#### Getting Started with "react-rating" Create React App

[react rating my demo](https://vermillion-cocada-8ce3b2.netlify.app/)

[react rating demo](http://dreyescat.github.io/react-rating/)

[react rating github](https://github.com/dreyescat/react-rating)

```bash
    npm install --save react-rating

    import Rating from 'react-rating';
    import { faStar } from '@fortawesome/free-solid-svg-icons'
    import { FontAwesomeIcon } from "@fortawesome/react-fontawesome";

    <Rating
        initialRating={3.5}
        emptySymbol={<FontAwesomeIcon icon={faStar} />}
        fullSymbol={<FontAwesomeIcon style={{color: 'goldenrod'}} icon={faStar} />}
        readonly
    ></Rating>

```
