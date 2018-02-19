# (dechartered) `Intl` Working Group

![Intl logo](img/Intl.png)

# This WG has been [dechartered](https://github.com/nodejs/TSC/issues/353) —
# Please see [nodejs/i18n](https://github.com/nodejs/i18n) for current activity

 _(content kept for archival purposes)_

-----

## Mandate

The Intl Working Group is dedicated to support and improvement of 
Internationalization (i18n) and Localization (l10n) in Node.js.

This WG's responsibility would be the 
implementation of internationalization support (including but not limited to 
Ecma-402) within Node.js itself, as well as ensuring compliance with standards
such as Unicode, CLDR, and other globalization efforts.

*Internationalization* here refers to the ability for Node.js to properly
process textual content written in human languages (for example, Unicode
character processing) as well as to provide services which respect the user’s
cultural and socio-linguistic preferences (such as the particular way that dates
and times would be displayed).

*Localization* here refers to the ability for Node.js and its modules and
applications to be actually translated into specific human languages. It is the
responsibility of this WG to provide the infrastructure necessary to allow such
translations to take place, such as message bundles and message formatting.

Note, however it is not in the scope
of this WG to perform the actual translation (or localization) of Node.js, its
documentation and websites, nor of modules or applications built using Node.js.

Specifically, this mission is distinct from that of the various i18n working groups
that are involved with translation of various project assets such as 
documentation and the website to benefit the global community.

In summary, this WGs responsibilities are:

1. Functionality & compliance (standards: ECMA, Unicode…)
2. Support for Globalization and Internationalization issues that come up in the tracker  
3. Guidance and Best Practices  
4. Refinement of existing `Intl` implementation 

### Example items in scope

* [Converged ICU/Intl enablement](https://github.com/nodejs/node/issues/26)
* [Adopt Globalize for i18n](https://github.com/nodejs/io.js/issues/1494)
* [System calls return non-normalized unicode strings](https://github.com/nodejs/io.js/issues/2165)

## Liaison relationships

The WG will pursue formal or informal relationships with other WGs or
other bodies as appropriate, which may include but is not limited to:

* v8 Intl engineering group
* W3C Internationalization group
* jQuery globalize

## Items out of scope

The Intl Working Group is not responsible for, but may benefit from
interaction/liaison with those interested in, the following:

* Translation of Node.js documentation, messages, and other materials into
specific languages.
* Outreach and user assistance given to users in specific languages.

## Current WG Members
  + Caridy Patiño (@caridy)
  + Daijirō Wachi (@watilde)
  + James Snell (@jasnell)
  + Kevin Jose Martin (@KevinMartin)
  + Michael Dawson (@mhdawson) 
  + Rafael Xavier de Souza (@rxaviers) 
  + Rick Waldron (@rwaldron)
  + Steven Atkin (@stevenatkin)
  + Steven R. Loomis (@srl295) Facilitator

If you would like to join this group, please comment on [this issue](https://github.com/nodejs/Intl/issues/5) 
or submit a pull request.
