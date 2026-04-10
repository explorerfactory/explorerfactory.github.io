---
layout: page
title: Contact
subtitle: Please fill in this form and we will get back to you asap.
date: 2026-04-10
last-updated: 2026-04-10
readtime: false
share-title: EXPLORER FACTORY | Your Memories, Mapped.
share-description: Custom Coordinate Clothing & Gear | Gifts for Travelers
share-img: /assets/img/explorerfactory_logo.png
social-share: false
---
<form action="https://api.web3forms.com/submit" method="POST" id="contact-form">

    <input type="hidden" name="access_key" value="6c9b08e4-96b1-4f4e-a69c-7daf8d88e9ba">
    <!-- Web3Forms will now use the "subject" from the dropdown automatically -->

    <div class="form-group">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" placeholder="Your name" required>
    </div>

    <div class="form-group">
        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="Your email address" required>
    </div>

    <div class="form-group">
        <label for="subject">Subject</label>
        <select id="subject" name="subject" required>
            <option value="" disabled selected>Select a topic...</option>
            <option value="Order Inquiry">Order Status / Inquiry</option>
            <option value="Product Question">Product Information</option>
            <option value="Shipping & Returns">Shipping & Returns</option>
            <option value="Partnership">Partnership / Collaboration</option>
            <option value="Technical Issue">Website / Technical Issue</option>
            <option value="General Inquiry">General Question</option>
        </select>
    </div>

    <div class="form-group">
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="3" placeholder="Your message" style="resize: none;" oninput="this.style.height = 'auto'; this.style.height = (this.scrollHeight) + 'px';" required></textarea>
    </div>

    <div class="h-captcha" data-captcha="true"></div>

    <button type="submit">SEND</button>
</form>

<style>
    #contact-form {
        max-width: 100%;
        margin: 20px auto;
        padding: 25px;
        background-color: #FEF4DA;
        border: 1px solid #e6e5e2;
        border-radius: 8px;
    }

    .form-group {
        margin-bottom: 20px;
    }

    label {
        display: block;
        margin-bottom: 8px;
        font-weight: 600;
        color: #404040;
        font-size: 0.85rem;
        text-transform: uppercase;
        letter-spacing: 1px;
    }

    /* Added select here to match your other inputs */
    input[type="text"],
    input[type="email"],
    select, 
    textarea {
        width: 100%;
        padding: 12px;
        border: 1px solid #e6e5e2;
        border-radius: 8px;
        background-color: #ffffff;
        font-size: 1rem;
        color: #404040;
        box-sizing: border-box;
        transition: border-color 0.3s ease;
        font-family: inherit;
    }

    /* Ensure the dropdown height matches the inputs exactly */
    select {
        height: 46px; 
        cursor: pointer;
    }

    input:focus, 
    select:focus,
    textarea:focus {
        outline: none;
        border-color: #404040; /* Darker border on focus for better UX */
    }

    button[type="submit"] {
        width: 100%;
        padding: 14px;
        background-color: #404040;
        color: #faf8f5;
        border: none;
        border-radius: 8px;
        font-size: 1rem;
        font-weight: bold;
        cursor: pointer;
        transition: background-color 0.3s ease;
    }

    button[type="submit"]:hover {
        background-color: #FF7518;
    }

    .h-captcha {
        margin-bottom: 20px;
        display: flex;
        justify-content: center;
    }
</style>

<script src="https://web3forms.com/client/script.js" async defer></script>