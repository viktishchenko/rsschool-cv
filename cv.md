## **Viktor Tishchenko**

+7 904 325 84 51 · Viber · WhatsApp ·
Telegram · Omsk, Russian Federation · web22pro@gmail.com

### Summary

Давно выяснено, что при оценке дизайна и композиции читаемый текст мешает сосредоточиться. Lorem Ipsum используют потому, что тот обеспечивает более или менее стандартное заполнение шаблона, а также реальное распределение букв и пробелов в абзацах, которое не получается при простой дубликации.

### Skills

- Languages: HTML, CSS, Javascript (basics), PHP (basics);
- Web libs: Bootstrap, jQuery, Materialize;
- Responsive design;
- Web Dev tools: Gulp, npm;
- VCS: Git basics;
- DB: MySQL, MongoDB Atlas (basic set of queries);
- Graphic editors: ADOBE Photoshop, CorelDRAW, Google Web Designer;
- Search engine optimization

### Code Example

```
import React, { useState } from 'react';
import { render } from 'react-dom';
import { DatePicker, message } from 'antd';
import 'antd/dist/antd.css';
import './index.css';

const App = () => {
  const [date, setDate] = useState(null);
  const handleChange = value => {
    message.info(`Selected Date: ${value ? value.format('YYYY-MM-DD') : 'None'}`);
    setDate(value);
  };
  return (
    <div style={{ width: 400, margin: '100px auto' }}>
      <DatePicker onChange={handleChange} />
      <div style={{ marginTop: 16 }}>
        Selected Date: {date ? date.format('YYYY-MM-DD') : 'None'}
      </div>
    </div>
  );
};

render(<App />, document.getElementById('root'));
```

### Education

- **Faculty of Economics and Management -** Omsk State Technical University, Russian Federation

  ### Language competencies

* Russian: native language

* English: intermediate (B1)
