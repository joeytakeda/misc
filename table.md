<table>
                  <tr>
                     <td colspan="2"><span class="label"><span class="gi">back</span> </span>(back matter) contains any appendixes, etc. following the main part of a text. 
                        [<a href="http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-back.html">TEI Guidelines</a>]
                        
                     </td>
                  </tr>
                  <tr>
                     <td><span class="label">Attributes</span></td>
                     <td><span lang="en">Attributes </span><a href="#att.global">att.global</a> (<span class="attribute">@xml:id</span>, <span class="attribute">@n</span>, <span class="attribute">@xml:lang</span>, <span class="attribute">@xml:base</span>, <span class="attribute">@xml:space</span>)  (<a href="#att.global.rendition">att.global.rendition</a> (<span class="attribute">@rend</span>, <span class="attribute">@style</span>, <span class="attribute">@rendition</span>))  (<a href="#att.global.analytic">att.global.analytic</a> (<span class="attribute">@ana</span>))  (<a href="#att.global.responsibility">att.global.responsibility</a> (<span class="attribute">@cert</span>, <span class="attribute">@resp</span>))  (<a href="#att.global.source">att.global.source</a> (<span class="attribute">@source</span>)) <a href="#att.declaring">att.declaring</a> (<span class="attribute">@decls</span>) 
                     </td>
                  </tr>
                  <tr>
                     <td><span class="label">Contained by</span></td>
                     <td>
                        <div>
                           <div>
                              <div><span class="label">textstructure: </span><a href="#text">text</a></div>
                           </div>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td><span class="label">May contain</span></td>
                     <td>
                        <div>
                           <div><span class="label">core: </span><a href="#gap">gap</a> <a href="#head">head</a> <a href="#lb">lb</a> <a href="#list">list</a> <a href="#listBibl">listBibl</a> <a href="#milestone">milestone</a> <a href="#note">note</a> <a href="#p">p</a> <a href="#pb">pb</a></div>
                           <div><span class="label">textstructure: </span><a href="#byline">byline</a> <a href="#closer">closer</a> <a href="#div">div</a> <a href="#docAuthor">docAuthor</a> <a href="#docDate">docDate</a> <a href="#docTitle">docTitle</a> <a href="#epigraph">epigraph</a> <a href="#titlePage">titlePage</a> <a href="#titlePart">titlePart</a> <a href="#trailer">trailer</a></div>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td><span class="label">Note</span></td>
                     <td>
                        <p>Because cultural conventions differ as to which elements are grouped as back matter
                           and which as front matter, the content models for the <a href="#back" class="gi">back</a> and <a href="#front" class="gi">front</a> elements are identical.
                        </p>
                     </td>
                  </tr>
                  <tr>
                     <td><span class="label">Example</span></td>
                     <td>
                        <div id="index.xml-egXML-d38e22848" class="pre egXML_valid"><span class="element">&lt;back&gt;</span><br/> <span class="element">&lt;div <span class="attribute">type="</span><span class="attributevalue">appendix</span>"&gt;
                              </span><br/>  <span class="element">&lt;head&gt;</span>The Golden Dream or, the Ingenuous Confession<span class="element">&lt;/head&gt;</span><br/>  <span class="element">&lt;p&gt;</span>TO shew the Depravity of human Nature, and how apt the Mind is to be misled by Trinkets<br/>     and false Appearances, Mrs. Two-Shoes does acknowledge, that after she became
                           rich, she<br/>     had like to have been, too fond of Money <br/><span class="comment">&lt;!-- .... --&gt;</span><br/>  <span class="element">&lt;/p&gt;</span><br/> <span class="element">&lt;/div&gt;</span><br/><span class="comment">&lt;!-- ... --&gt;</span><br/> <span class="element">&lt;div <span class="attribute">type="</span><span class="attributevalue">epistle</span>"&gt;
                              </span><br/>  <span class="element">&lt;head&gt;</span>A letter from the Printer, which he desires may be inserted<span class="element">&lt;/head&gt;</span><br/>  <span class="element">&lt;salute&gt;</span>Sir.<span class="element">&lt;/salute&gt;</span><br/>  <span class="element">&lt;p&gt;</span>I have done with your Copy, so you may return it to the Vatican, if you please;<br/>  <br/><span class="comment">&lt;!-- ... --&gt;</span><br/>  <span class="element">&lt;/p&gt;</span><br/> <span class="element">&lt;/div&gt;</span><br/> <span class="element">&lt;div <span class="attribute">type="</span><span class="attributevalue">advert</span>"&gt;
                              </span><br/>  <span class="element">&lt;head&gt;</span>The Books usually read by the Scholars of Mrs Two-Shoes are these and are sold at
                           Mr<br/>     Newbery's at the Bible and Sun in St Paul's Church-yard.<span class="element">&lt;/head&gt;</span><br/>  <span class="element">&lt;list&gt;</span><br/>   <span class="element">&lt;item <span class="attribute">n="</span><span class="attributevalue">1</span>"&gt;
                              </span>The Christmas Box, Price 1d.<span class="element">&lt;/item&gt;</span><br/>   <span class="element">&lt;item <span class="attribute">n="</span><span class="attributevalue">2</span>"&gt;
                              </span>The History of Giles Gingerbread, 1d.<span class="element">&lt;/item&gt;</span><br/><span class="comment">&lt;!-- ... --&gt;</span><br/>   <span class="element">&lt;item <span class="attribute">n="</span><span class="attributevalue">42</span>"&gt;
                              </span>A Curious Collection of Travels, selected from the Writers of all Nations,<br/>       10 Vol, Pr. bound 1l.<span class="element">&lt;/item&gt;</span><br/>  <span class="element">&lt;/list&gt;</span><br/> <span class="element">&lt;/div&gt;</span><br/> <span class="element">&lt;div <span class="attribute">type="</span><span class="attributevalue">advert</span>"&gt;
                              </span><br/>  <span class="element">&lt;head&gt;</span>By the KING's Royal Patent, Are sold by J. NEWBERY, at the Bible and Sun in St.<br/>     Paul's Church-Yard.<span class="element">&lt;/head&gt;</span><br/>  <span class="element">&lt;list&gt;</span><br/>   <span class="element">&lt;item <span class="attribute">n="</span><span class="attributevalue">1</span>"&gt;
                              </span>Dr. James's Powders for Fevers, the Small-Pox, Measles, Colds, &amp;amp;c. 2s.<br/>       6d<span class="element">&lt;/item&gt;</span><br/>   <span class="element">&lt;item <span class="attribute">n="</span><span class="attributevalue">2</span>"&gt;
                              </span>Dr. Hooper's Female Pills, 1s.<span class="element">&lt;/item&gt;</span><br/><span class="comment">&lt;!-- ... --&gt;</span><br/>  <span class="element">&lt;/list&gt;</span><br/> <span class="element">&lt;/div&gt;</span><br/><span class="element">&lt;/back&gt;</span></div>
                     </td>
                  </tr>
               </table>
