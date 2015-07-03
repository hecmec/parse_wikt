# parse_wikt
Experminente mit wiktionary data api

the wiktionary api returns json, but the rawContent of the Translation part is just unstructured text

	{
	  "English": {
	    "Etymology": {
	      "rawContent": "\nFrom {{etyl|frm|en}} {{term|sublime||lang=frm}}, from {{etyl|la|en}} {{term/t|la|sublīmis||high}}, from {{term|sub-||lang=la|up to\", \"upwards}} + uncertain, often identified with {{etyl|la|en}} {{term/t|la|līmis}}, ablative singular of {{term/t|la|līmus||oblique}} or {{term/t|la|līmen||threshold\", \"entrance\", \"lintel}}\n\n"
	    },
	    "Pronunciation": {
	      "rawContent": "\n* {{audio|en-us-sublime.ogg|Audio (US)}}\n* {{rhymes|aɪm}}\n\n"
	    },
	    "Adjective": {
	      "Translations": {
	        "rawContent": "\n{{trans-top|noble and majestic}}\n	* French: {{t+|fr|sublime}}\n * German: {{t+|de|hehr}}, {{t+|de|erhaben}}, {{t+|de|nobel}}, {{t+|de|sublim}}\n * Russian: {{t+|ru|возвышенный|tr=vozvýšennyj|sc=Cyrl}}, {{t+|ru|величественный|tr=velíčestvennyj|sc=Cyrl}}\n* Spanish: {{t+|es|sublime}}\n{{trans-bottom}}
			{{trans-top|impressive and awe-inspiring}}\n * German: {{t+|de|grandios}}, {{t|de|vortrefflich}}\n * Hungarian: {{t+|hu|fenséges}}, {{t+|hu|emelkedett}}, {{t+|hu|fennkölt}}, {{t+|hu|magasztos}}\n
			"Senses": [
			"noble and majestic": {
				"French":["sublime"],
				"German": ["hehr","erhaben","nobel","sublim"],
				"Russian": ["возвышенный","величественный"],
				"Spanish": ["sublime"],
			},
			"impressive and awe-inspiring": {
				"German": ["grandios","vortrefflich"]
			}
			]
	      }
	    },
	    "Noun": {
	      "Translations": {
	        "rawContent": "\n{{trans-top|something sublime}}\n* German: {{t|de|Erhabene|n}}\n* Portuguese: {{t+|pt|sublime|m}}\n{{trans-mid}}\n* Russian: {{t|ru|возвышенное|n}}\n{{trans-bottom}}\n\n"
	      }
	    },
	    "Verb": {
	      "Related terms": {
	        "rawContent": "\n* [[sublimation]]\n\n"
	      },
	      "Translations": {
	        "rawContent": "\n{{trans-top|to sublimate}}\n* Danish: {{t|da|sublimere}}\n* Finnish: {{t|fi|sublimoitua}}\n* French: {{t+|fr|sublimer}}\n* German: {{t+|de|sublimieren}}\n* Macedonian: {{t|mk|возвишува|tr=vozvíšuva}}, {{t|mk|сублимира|tr=sublimíra}}\n* Russian: {{t+|ru|сублимировать}}, {{t+|ru|возгонять}}\n{{trans-mid}}\n* Serbo-Croatian:\n*: Cyrillic: {{t|sh|у̀звӣшен|m}}\n*: Roman: {{t|sh|ùzvīšen|m}}\n* Slovene: {{t+|sl|veličasten}}\n* Spanish: {{t+|es|sublimar}}\n{{trans-bottom}}\n\n"
	      }
	    },
	    "Anagrams": {
	      "rawContent": "\n* [[blueism#English|blueism]]\n\n----\n\n"
	    }
	  },
	  "Danish": {
	    "Adjective": {
	      "rawContent": "\n{{head|da|adjective form}}\n\n# {{form of|definite|sublim|lang=da}}\n# {{plural of|sublim|lang=da}}\n\n----\n\n"
	    }
	  },
	  "French": {
	    "Pronunciation": {
	      "rawContent": "\n* {{audio|Fr-sublime.ogg|Audio}}\n\n"
	    },
	    "Adjective": {
	      "rawContent": "\n{{fr-adj|mf}}\n\n# [[#English|sublime]], [[extraordinary]]\n\n"
	    },
	    "Verb": {
	      "rawContent": "\n{{fr-verb-form}}\n\n# {{conjugation of|sublimer||1|s|pres|ind|lang=fr}}\n# {{conjugation of|sublimer||3|s|pres|ind|lang=fr}}\n# {{conjugation of|sublimer||1|s|pres|sub|lang=fr}}\n# {{conjugation of|sublimer||3|s|pres|sub|lang=fr}}\n# {{conjugation of|sublimer||2|s|imp|lang=fr}}\n\n----\n\n"
	    }
	  },
	  "Italian": {
	    "Adjective": {
	      "rawContent": "\n{{it-adj|sublim|e|i}}\n\n# [[#English|sublime]]\n\n====Related terms====\n* [[sublimità]]\n\n----\n\n"
	    }
	  },
	  "Latin": {
	    "Adjective": {
	      "rawContent": "\n{{la-adj-form|sublīme}}\n\n# {{inflection of|sublīmus||voc|m|s|lang=la}}\n\n----\n\n"
	    }
	  }
	}


