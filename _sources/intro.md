#
<html>
    <head>
        <title> Spacetelescope jdat_notebooks Index </title>
<meta http-equiv="content-type" content="text.html"; charset=utf-8">

<!-- Custom Style -->
<link rel="stylesheet" href="main.css">
<link href="https://fonts.googleapis.com/css2?family=Overpass:wght@400;900&display=swap" rel="stylesheet">

<!-- Mobile Configuration Tags -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Summary Content -->
<meta name="description" content="A space for Astronomy Notebooks" />
<meta name="keywords" content="stsci,spacetelescope,jupyter,notebooks,astronomy" />
<meta name="author" content="Spacetelescope" />

<!-- Google SEO -->
<!-- Details: https://support.google.com/webmasters/answer/79812?hl=en -->
<meta name="googlebot" content="index" />

<!-- Open Graph -->
<!-- https://ogp.me/ -->
<meta property="og:title" content="Spacetelescope jdat_notebooks Index" />
<meta property="og:url" content="https://spacetelescope.github.io/jdat_notebooks" />
<meta property="og:description" content="A space for Astronomy Notebooks" />
<meta property="og:type" content="website" />
<meta property="og:locale" content="en" />
<meta property="og:author" content="Spacetelescope" />
    </head>
    <body>
    <section class="notebooks">
 <div id="readme" class="Box-body readme blob js-code-block-container p-5 p-xl-6 gist-border-0">
    <article class="markdown-body entry-content container-lg" itemprop="text"><a name="user-content-james-webb-space-telescope-data-analysis-tool-notebooks"></a>
<h2><a id="user-content-james-webb-space-telescope-data-analysis-tool-notebooks" class="anchor" aria-hidden="true" href="#james-webb-space-telescope-data-analysis-tool-notebooks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>James Webb Space Telescope Data Analysis Tool Notebooks</h2>
<p>The <code>jdat_notebooks</code> repository contains notebooks illustrating workflows for post-pipeline analysis of JWST data. Some of the notebooks also illustrate generic analysis workflows that are applicable to data from other observatories as well. This repository and the notebooks are one component of STScI's larger <a href="https://jwst-docs.stsci.edu/jwst-post-pipeline-data-analysis" rel="nofollow">Data Analysis Tools Ecosystem</a>.</p>
<p>The following table summarizes the notebooks currently available.  Most links will take you to rendered versions of the notebooks, which require no special tools beyond your web browser.  To download and execute the notebooks, <a href="https://github.com/git-guides/git-clone">clone</a> this <a href="https://github.com/spacetelescope/jdat_notebooks">repository</a> to your local computer. Most of the notebooks
rely on packages that can be installed using <a href="https://pip.pypa.io/en/stable/" rel="nofollow">pip</a>. The version
dependencies are listed in the environment.yaml and in the requirements file in each notebook folder.</p>
<table>




<thead valign="bottom">
<tr><th colspan="2">JWST Science Analysis Notebooks</th>
</tr>
<tr><th>Notebook</th>
<th>Description</th>
</tr>
<tr><th colspan="2">Cross-Instrument</th>
</tr>
</thead>
<tbody valign="top">
<tr><td>asdf</td>
<td><ul>
<li>Use case: create ASDF (Advanced Scientific Data Format) file from FITS file.</li>
<li>Data: CANDELS image of the COSMOS field.</li>
<li>Tools: asdf, gwcs, astrocut.</li>
<li>Cross-instrument: all instruments.</li>
</ul>
</td>
</tr>
<tr><td>Background Estimation</td>
<td><ul>
<li>Use case: estimate the sky background in complex scenes.</li>
<li>Data: images with pathological background pattern created in the notebook.</li>
<li>Tools: photutils</li>
<li>Cross-instrument: all instruments.</li>
</ul>
</td>
</tr>
<tr><td>Redshift
Cross-Corr</td>
<td><ul>
<li>Use case: reproduce the workflow of the IRAF task XCORFIT to measure redshift.</li>
<li>Data: LEGA-C spectra and galaxy template spectra; optical rest-frame.</li>
<li>Tools: specutils.</li>
<li>Cross-instrument: all instruments.</li>
</ul>
</td>
</tr>
<tr><td>Querying MAST</td>
<td><ul>
<li>Use case: How to submit a NIRSpec MAST Query using python.</li>
<li>Data:</li>
<li>Tools: mast, astroquery.</li>
<li>Cross-instrument: all instruments.</li>
</ul>
</td>
</tr>
<tr><td>Specviz GUI</td>
<td><ul>
<li>Use case: How to inspect and export spectra in Specviz GUI.</li>
<li>Data: NIRISS simulation  generated with the code MIRAGE.</li>
<li>Tools: specutils, jdaviz.</li>
<li>Cross-instrument: all instruments.</li>
</ul>
</td>
</tr>
<tr><td>IFU Cube Fitting</td>
<td><ul>
<li>Use case: continuum and emission-line modeling of galaxy IFU spectra.</li>
<li>Data: Spitzer IRS on Messier 58.</li>
<li>Tools: specutils, custom functions.</li>
<li>Cross-instrument: MIRI, NIRSpec.</li>
</ul>
</td>
</tr>
<tr><td colspan="2">NIRCam</td>
</tr>
<tr><td>Multiband Extended Aperture Photometry</td>
<td><ul>
<li>Use case: measure extended galaxy photometry in a field.</li>
<li>Data: Simulated NIRCam images from JADES GTO extragalactic blank field.</li>
<li>Tools: photutils.</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
<tr><td>Crowded Field Aperture Photometry</td>
<td><ul>
<li>Use case: Crowded field imaging with Aperture-fitting photometry.</li>
<li>Data: Simulated NIRCam images of LMC astrometric calibration field.</li>
<li>Tools: jwst pipeline, photutils.</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
<tr><td>PSF Photometry</td>
<td><ul>
<li>Use case: Crowded field imaging with PSF-fitting photometry.</li>
<li>Data: Simulated NIRCam images of LMC astrometric calibration field.</li>
<li>Tools: webbpsf, photutils.</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
<tr><td>PSF Matching Photometry</td>
<td><ul>
<li>Use case: Crowded field imaging with PSF-fitting photometry.</li>
<li>Data: Simulated NIRCam images of LMC astrometric calibration field.</li>
<li>Tools: webbpsf, photutils.</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
<tr><td colspan="2">NIRISS</td>
</tr>
<tr><td>WFSS Spectra
Notebook 0
Notebook 1
Notebook 2
Notebook 3</td>
<td><ul>
<li>Use case: Optimal extraction and analysis of grism spectra.</li>
<li>Data: Simulated NIRISS spectra of a galaxy cluster</li>
<li>Tools: specutils         .</li>
<li>Cross-instrument: NIRSpec.</li>
</ul>
</td>
</tr>
<tr><td>MOS spctra</td>
<td><ul>
<li>Use case: Emission-line measurements and template matching on 1D spectra.</li>
<li>Data: LEGA-C spectra and galaxy template spectra; optical rest-frame.</li>
<li>Tools: specutils.</li>
<li>Cross-instrument: NIRSpec.</li>
</ul>
</td>
</tr>
<tr><td>SOSS Transiting Exoplanet</td>
<td><ul>
<li>Use case: Primary transit of an exoplanet.</li>
<li>Data: Simulated transit using awesomesoss.</li>
<li>Tools: jwst pipeline, juliet.</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
<tr><td>AMI
Binary
Star</td>
<td><ul>
<li>Use case: Find the binary parameters of AB Dor.</li>
<li>Data: Simulated MIRAGE data for a binary point source.</li>
<li>Tools: jwst pipeline, nrm_analysis.</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
<tr><td colspan="2">NIRSpec</td>
</tr>
<tr><td>IFU Analysis</td>
<td><ul>
<li>Use case: Continuum and emission-line modeling of AGN; 1.47-1.87um.</li>
<li>Data: NIFS on Gemini; NGC 4151.</li>
<li>Tools: specutils, cubeviz.</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
<tr><td>MOS Optimal Extraction</td>
<td><ul>
<li>Use case: Optimal spectral extraction.</li>
<li>Data: Simulated NIRSpec MOS data; point sources.</li>
<li>Tools: jwst pipeline</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
<tr><td>MOS Pre-Imaging</td>
<td><ul>
<li>Use case: Simulation of NIRCam pre-imaging for NIRSpec.</li>
<li>Data: Simulated NIRCam images of LMC astrometric calibration field.</li>
<li>Tools: jwst pipeline.</li>
<li>Cross-instrument: NIRCam.</li>
</ul>
</td>
</tr>
<tr><td>BOTS Transiting Exoplanet</td>
<td><ul>
<li>Use case: Primary transit of an exoplanet.</li>
<li>Data: Simulated NIRSpec data from ground-based campaign.</li>
<li>Tools:</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
<tr><td>IFU Optimal Extraction</td>
<td><ul>
<li>Use case: Optimal spectral extraction.</li>
<li>Data: Simulated data of faint (quasar) point source.</li>
<li>Tools:  jwst, scipy, specutils, jdaviz, photutils, astropy.io, astropy.wcs</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
<tr><td colspan="2">MIRI</td>
</tr>
<tr><td>LRS Optimal Extraction</td>
<td><ul>
<li>Use case: Optimal spectral extraction.</li>
<li>Data: MIRISim simulated spectra.</li>
<li>Tools: jwst pipeline, gwcs.</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
<tr><td>IFU Cube 1</td>
<td><ul>
<li>Use case: Extract spatial-spectral features from IFU cube.</li>
<li>Data: KMOS datacube of point sources in the LMC.</li>
<li>Tools: specutils, spectral_cube, photutils.</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
<tr><td>IFU Cube 2</td>
<td><ul>
<li>Use case: Photutils to automatically detect point sources and extract photometry</li>
<li>Data: ALMA 13CO data cubes.</li>
<li>Tools: specutils, spectral_cube, photutils.</li>
<li>Cross-instrument:</li>
</ul>
</td>
</tr>
</tbody>
</table>
<a name="user-content-help"></a>
<h2><a id="user-content-help" class="anchor" aria-hidden="true" href="#help"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Help</h2>
<p>If you uncover any issues or bugs, you can open a GitHub ticket.  For faster responses, however, we encourage you to submit a JWST Help Desk Ticket: jwsthelp.stsci.edu</p>
<a name="user-content-contributing"></a>
<h2><a id="user-content-contributing" class="anchor" aria-hidden="true" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Contributing</h2>
<p>Contributions are welcome from both the scientist and developer community.  If you wish to contribute fixes or clarifications to existing notebooks, feel free to do so directly to this repository.  If you wish to contribute new notebooks or major reworks of existing notebooks, we refer you to <a href="https://github.com/spacetelescope/jdat_notebooks">jdat_notebooks</a>.  For details on how to provide such contributions, see the <a href="https://github.com/spacetelescope/jdat_notebooks/blob/main/CONTRIBUTING.rst">contributing instructions</a>.</p>
<p>The notebooks attempt to utilize a number of software packages supported by STScI, including <a href="https://www.astropy.org" rel="nofollow">Astropy</a>, <a href="http://docs.glueviz.org/en/stable/index.html" rel="nofollow">glue</a>, <a href="https://ginga.readthedocs.io/en/latest/" rel="nofollow">ginga</a>, <a href="https://photutils.readthedocs.io" rel="nofollow">photutils</a>, <a href="https://specutils.readthedocs.io/en/stable/" rel="nofollow">specutils</a>, <a href="http://astroimtools.readthedocs.io" rel="nofollow">astroimtools</a>, <a href="http://imexam.readthedocs.io" rel="nofollow">imexam</a>, <a href="https://jdaviz.readthedocs.io/en/latest/" rel="nofollow">jdaviz</a>, <a href="http://asdf.readthedocs.io/en/latest/" rel="nofollow">asdf</a>, <a href="https://gwcs.readthedocs.io/en/latest/" rel="nofollow">gwcs</a>, and <a href="http://synphot.readthedocs.io/en/latest/index.html" rel="nofollow">synphot</a>.  Note jdaviz is STScI's JWST Data Analysis Visualization Tool, designed to be used with spectra, IFU cubes, and multi-object spectroscopy (MOS).</p>
  </body>
<html>
