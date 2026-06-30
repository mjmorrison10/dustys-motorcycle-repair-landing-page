# Instructions for Dusty

**Website:** Dusty's Motorcycle Service & Repair  
**Owner:** Dustin Dodds  
**Address:** 130 S Lemon Street, Orange, CA 92866

This document contains everything you need to finalize and launch your new website.

---

## 1. Formspree Email Integration (Required)

Your contact form is currently connected to **Formspree**, which will email you every time someone submits a lead.

### Steps to Activate:

1. Go to [https://formspree.io](https://formspree.io) and create a free account.
2. Create a new form.
3. Copy the **Form ID** (it will look something like `https://formspree.io/f/xxxxxxx`).
4. Open the file `index.html` in your repository.
5. Find this line near the form:
   ```html
   <form action="https://formspree.io/f/your-form-id" method="POST">
   ```
6. Replace `your-form-id` with your actual Form ID.
7. Save the file and push the change to GitHub.

Once this is done, the form will start sending leads directly to your email.

---

## 2. Form Testing

After setting up Formspree:

- Submit a test form on the live site.
- Check your email to confirm leads are arriving.
- Make sure the success message appears after submission.

---

## 3. Future Agent Notes

This section will be updated by other agents as the project continues.

### Content Strategist
- Testimonials section has been added using real customer feedback themes.
- Consider adding 1–2 more real reviews if you have them.

### Lead Capture Specialist
- Form has been optimized for conversion.
- Secondary “Text Dusty” option is available.

### CRM Integration Agent
- Formspree has been implemented as the primary lead delivery method.
- Optional: Add SMS notifications later if desired.

---

## 4. Next Steps (Recommended Order)

1. Set up Formspree (see Section 1)
2. Test the form
3. Review the live site on mobile
4. Add more testimonials if available
5. Launch the website

---

**Document Version:** 1.0  
**Last Updated:** June 30, 2026

This document will grow as more agents contribute their instructions.