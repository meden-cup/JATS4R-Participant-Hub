# References / citations

References (citation of software/data/versions/law cases)

See [GitHub issues](https://github.com/JATS4R/elements/labels/references-citations).

Please add examples here.

Data Citations

## Nature Publishing Group


Example with CrossRef DOI URL as text and link

```xml

<ref-list content-type="data-citations">
  <ref id="d1">
    <element-citation>
      <source>Long Term Ecological Research Network</source>
      <ext-link ext-link-type="public-website" specific-use="url"
        xlink:href="http://dx.doi.org/10.6073/pasta/379a6cebee50119df2575c469aba19c5">http://dx.doi.org/10.6073/pasta/379a6cebee50119df2575c469aba19c5</ext-link>
      <year>2015</year>
      <collab>
        <contrib-group>
          <contrib>
            <name>
              <surname>Sharma</surname>
              <given-names>S.</given-names>
            </name>
          </contrib>
        </contrib-group>
      </collab>
      <etal/>
    </element-citation>
  </ref>
</ref-list>


```

Example with database entry ID as text and full URL as link

```xml

<ref id="d1">
  <element-citation>
    <source>Gene Expression Omnibus</source>
    <ext-link ext-link-type="geo" specific-use="url" xlink:href="http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE59088">GSE59088</ext-link>
    <year>2014</year>
    <collab>
      <contrib-group>
        <contrib>
          <name>
            <surname>Schjerling</surname>
            <given-names>P.</given-names>
          </name>
        </contrib>
        <contrib>
          <name>
            <surname>Vissing</surname>
            <given-names>K.</given-names>
          </name>
        </contrib>
      </contrib-group>
    </collab>
  </element-citation>
</ref>


```

Examples with database entry ID as text and link (Full URL in HTML from lookup of database ID in @ext-link-type in ontology)


```xml

<ref id="d5">
  <element-citation>
    <source>ArrayExpress</source>
    <ext-link ext-link-type="arrayexpress.platform" specific-use="id" xlink:href="E-MTAB-2332">E-MTAB-2332</ext-link>
    <year>2014</year>
    <collab>
      <contrib-group>
        <contrib>
          <name>
            <surname>The Rat Genome Sequencing and Mapping Consortium</surname>
            <given-names/>
          </name>
        </contrib>
      </contrib-group>
    </collab>
  </element-citation>
</ref>
....
<ref id="d7">
  <element-citation>
    <source>Biological Magnetic Resonance Data Bank</source>
    <ext-link ext-link-type="bmrb" specific-use="id" xlink:href="1002">1002</ext-link>
    <year>2014</year>
    <collab>
      <contrib-group>
        <contrib>
          <name>
            <surname>Chazin</surname>
            <given-names>Walter</given-names>
          </name>
        </contrib>
      </contrib-group>
    </collab>
  </element-citation>
</ref>
....
<ref id="d30">
  <element-citation>
    <source>PeptideAtlas</source>
    <year>2014</year>
    <ext-link ext-link-type="peptideatlas" specific-use="id" xlink:href="PASS00416">PASS00416</ext-link>
    <collab>
      <contrib-group>
        <contrib>
          <name>
            <surname>Metz</surname>
            <given-names>T.</given-names>
          </name>
        </contrib>
      </contrib-group>
    </collab>
  </element-citation>
</ref>

```

##eLife

Example 1

```
<ref id="bib46">
  <element-citation publication-type="data">
    <person-group person-group-type="author">
      <name><surname>Ly</surname>
        <given-names>T</given-names></name>, <name><surname>Endo</surname>
        <given-names>A</given-names></name>, <name>
        <surname>Lamond</surname><given-names>Angus I</given-names></name>
    </person-group>
    <year>2014</year>
    <source>Proteomics dataset</source>
    <ext-link ext-link-type="uri" xlink:href="http://proteomecentral.proteomexchange.org"
      >http://proteomecentral.proteomexchange.org</ext-link>
  </element-citation>
</ref>
```


Example 2

```
<ref id="bib46">
  <element-citation publication-type="web">
    <person-group person-group-type="author">
      <name>
        <surname>Schuman</surname>
        <given-names>M</given-names>
      </name>
      <name>
        <surname>Barthel</surname>
        <given-names>K</given-names>
      </name>
      <name>
        <surname>Baldwin</surname>
        <given-names>IT</given-names>
      </name>
    </person-group>
    <year>2012</year>
    <comment>Data from: Herbivory-induced volatiles function as defenses increasing
      fitness of the native plant <italic>Nicotiana attenuata</italic> in nature.
      Dryad Digital Repository.</comment>
    <ext-link ext-link-type="uri" xlink:href="http://dx.doi.org/10.5061/dryad.gs45f"
      >http://dx.doi.org/10.5061/dryad.gs45f</ext-link>
  </element-citation>
</ref>
```