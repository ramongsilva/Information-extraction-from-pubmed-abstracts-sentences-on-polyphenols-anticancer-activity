<h1>Information-extraction-from-pubmed-abstracts-sentences-about-polyphenols-anticancer-activity</h1>

<p>This repository contains all files used in the task of information extraction in pubmed abstracts sentences about the anti-cancer activity of polyphenols, using the R language.  The files are organized in the tasks of: NER (Named entity recognition) and AR (Association recognition).</p>

<h2>NER (Named entity recognition)</h2>
<ul>
  <li><a href='https://github.com/ramongsilva/Information-extraction-from-pubmed-abstracts-sentences-about-polyphenols-anticancer-activity/blob/main/ner-pubmed-abstracts-gh.R'>ner-pubmed-abstracts-gh.R</a>: R script for named entity recognition (NER) in pubmed abstracts about polyphenols anticancer activity, using PubTator API</li>
  <li><a href='https://github.com/ramongsilva/Information-extraction-from-pubmed-abstracts-sentences-about-polyphenols-anticancer-activity/blob/main/functions.R'>functions.R</a>: R script with auxiliar functions.</li>
   <li><a href='https://drive.google.com/file/d/1ZxQOrWO0SXXDvnnz4yIwlIhWNvw_uDVH/view'>db_total_project.db</a>:  SQLite Database needed to use the ner-pubmed-abstracts-gh.R script</li>
</ul>
<h3>NER (Named entity recognition) - Results</h3>
<ul>
    <li><a href='https://github.com/ramongsilva/Information-extraction-from-pubmed-abstracts-sentences-about-polyphenols-anticancer-activity/tree/main/entities-recognized'>entities-recognized</a>: folder with files resulted of NER task in information extraction with the <strong>named entities (polyphenols, cancers and genes) recognized on pubmed abstracts </strong> about polyphenols anticancer activity. This files are needed to use the association-recognition-pubmed-abstracts-gh.R script, on Association recognition task.</li>
  <li><a href='https://github.com/ramongsilva/Information-extraction-from-pubmed-abstracts-sentences-about-polyphenols-anticancer-activity/tree/main/entities-associations-sentences-recognized'>entities-associations-sentences-recognized</a>: folder with files resulted of NER task in information extraction with <strong> sentences recognized with entities (polyphenols, cancers and genes) associations on pubmed abstracts </strong> about polyphenols anticancer activity. This files are needed to use the association-recognition-pubmed-abstracts-gh.R script, on Association recognition task.</li>
</ul>



