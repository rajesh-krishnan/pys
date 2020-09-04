# pys: Patanjala Yogasutrani (पातञ्जल योगसुत्राणि)

## Prarthana (प्रार्थना) - Prayers 

```
ॐ सह नाववतु ।
सह नौ भुनक्तु ।
सह वीर्यं करवावहै ।
तेजस्वि नावधीतमस्तु मा विद्विषावहै ।
ॐ शान्तिः शान्तिः शान्तिः ॥
```

Om, together may we two (the teacher and the student) move (in our studies);
Together may we two relish (our studies);
Together may we two perform (our studies) with vigour;
May what has been studied by us be filled with the brilliance (of understanding); may it not give rise to hostility.
Om Peace, Peace, Peace.

\- From the Taittiriya Upanishad (तैत्तिरीय उपनिषद्) of the Yajur Veda (यजुर्वेदः)

```
योगेन चित्तस्य पदेन वाचां मलं शरीरस्य च वैद्यकेन । 
योपाकरोत्तं प्रवरं मुनीनां पतञ्जलिं प्राञ्जलिरानतोस्मि ॥
```

The impurities of the mind by yoga, speech by grammar and the impurities of the body through medical science,
he who is an expert in removing the impurities, to that most excellent of munis, Patanjali, I bow down with folded hands.

\- From a verse in Shivarama's commentary on the Yoga Sutras c. 18th century CE 

## Sankalpa (संकल्पः) - Intention Setting 

```
For removing all problems and pains in life,
for making Lord Parameshwara happy,
for the blessings and grace of Goddess Parvathi,
for the realization of the Self, and
for the peace and prosperity of all beings,
I am going to study the Yoga Sutras of Patanjali.
```

## Overview 

The objective of this work is to support the study of Yoga, which is one of the six astika darshanas of Santana Dharma; any academic or technical excursions are incidental to the core pursuit. Please note that I have not learned Sanskrit, vedangas, or yoga under a guru. Although I have a background in computer engineering, I have limited experience in computational linguistics, natural language processing, and web application development.

This repository will include resources for the study of the yoga sutras of Patanjali. Although the Patanjala yoga darshana is limited to using pratyaksha, anumana, and agama, we include translations and references to works by those who apply a vedantic interpretation (admitting upama, anupalabdhi, and athApatti as pramanas). Although the Patanjala Yoga Darshana is Agamic, we do not exclude translations and references to other Nigamic, Smriti, and Puranic sources; nor do we exclude sources from other Dharmic traditions such as Jaina, Bauddha, Veerashaiva, and Sikh, or other translators viewing this text through occidental or other hybrid lenses. We do not include commentaries, and only quote the translations in a comparative study with attribution, so I believe the quotations constitute fair use of the translations. This is a work in progress.

For now, we are attempting a client-side solution with static content that can be hosted locally or on a webserver; a modern browser supporting Javascript, HTML, and CSS should suffice. I was originally planning to release this software under the Unlicense, but unfortunately, the transliteration code by [Shreevatsa ji](http://shreevatsa.appspot.com/sanskrit/transliterate.html) has a GPLv2 or higher license. Note I have edited the transliteration code slightly to include the pranava (Om symbol).

### Ongoing Work
All of the machine readable data is in `patanjali.js`. We encode Sanskrit using ITRANS. Through a web page (`index.html`), we support navigation by chapter and verse. 
For each verse, the web page provides the chapter name, chapter number, verse number, and verse text (in Devnagari Unicode, ITRANS, and IAST formats). We provide a ITRANS to Devangarai Unicode and IAST transliteration tool. 

### Future Work
Once the original text is input, for each verse, we plan to provide the following, in order:
  1. Translation of the verse by Swami Satchidananda
  2. Translation of the verse by Swami Vivekananda
  3. Maharishi Veda Vyasa's commentary (in Devanagari Unicode, ITRANS, and IAST formats)
  4. Translation of the verse as well as Vyasa's commentary by Ganganath Jha
  5. Modern translations by others, including possibly, Gabriel Pradeepaka, B.K.S. Iyengar, T.K.V Desikachar, Christopher Isherwood, Swami Venkatesananda, Jaganath Carera, Swami Jnaneswara Bharati, Michael Beloved, and others
  6. Cross references to related verses
  7. Related references to BG, Yoga Upanishads, Bhagavadgita, Hatha Yoga Pradeepika, Yoga Vashista, and other texts
  8. Classical translations by Rajabhoja, Shivarama, and others
  9. Editor's notes
  10. Grammatical analysis
  11. Audio enunciation

To reduce the cognitive burden, we plan to make the subset of information displayed user-selectable. We plan to include bibliographic references, as well as a Sanskrit word index with occurrence counts and cross-references to verses. For the audio enunciation of each verse, it is to be determined whether the editor will record this, or use a text to speech tool. Similarly, it is to be determined whether the grammatical analysis is to be done manually, or by computer.
