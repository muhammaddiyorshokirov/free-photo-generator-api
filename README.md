!\[alt text\](https://badgen.net/badge/:subject/:status/:color?icon=github)

📸 Free Photo Generator API
===========================

Generate AI-powered images instantly using a simple GET request.

* * *

🔗 API Endpoint
---------------

`https://s741890.stase.uz/api/aip.php`

### 📥 How to Use

Send a GET request with the `prompt` parameter:

    https://s741890.stase.uz/api/aip.php?prompt=YOUR_PROMPT

#### 📝 Parameters

Parameter

Type

Description

`prompt`

string

Text describing the image to generate

**Example:**

    https://s741890.stase.uz/api/aip.php?prompt=anime+hot

* * *

### 📤 JSON Response

    {
      "status": "success",
      "prompt": "anime hot",
      "image_url": "https://s741890.stase.uz/api/img/1750965139_685d9b93a69b0.jpg",
      "file_name": "1750965139_685d9b93a69b0.jpg",
      "expires_in_seconds": 3600,
      "expires_at": "2025-06-26T23:12:19+03:00"
    }
    

#### 🔍 Response Description

Field

Description

`status`

Response status (success or error)

`prompt`

Your input prompt

`image_url`

Direct URL to the generated image

`file_name`

Name of the image file

`expires_in_seconds`

Time in seconds before the image is deleted

`expires_at`

Exact expiration time (ISO format)

* * *

🖼️ Example Output
------------------

Click to view the image:  
[https://s741890.stase.uz/api/img/1750965139\_685d9b93a69b0.jpg](https://s741890.stase.uz/api/img/1750965139_685d9b93a69b0.jpg)

* * *

🆓 Free & Open
--------------

No API keys required. No authentication. Use it freely for your projects, bots, or experiments.

* * *

📬 Contact
----------

For bug reports or feature requests, please open an issue in this repository.

> ⚠️ **Note:** Generated images are stored temporarily and will expire after `expires_in_seconds`.
