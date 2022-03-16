## Installation

The package can be installed via [npm](https://github.com/npm/cli):

```
npm install nice-select --save
```

## Usage

    import React, { useEffect} from "react";
    import niceSelect from "react-nice-select";

    import "react-nice-select/css/nice-select.css";

    const Example = () => {
      useEffect(() => {
    	niceSelect();
      }, []);
      return (
        <div />
      );
    };
