---
layout: onboard
---
<script>
$(function() {
  $('#open_btn').click();
})
</script>
<button id="open_btn" class="Button Button--default js-fr-dialogmodal-open u-hidden" aria-controls="modal">
  Apri
</button>
<div class="Dialog js-fr-dialogmodal" id="modal">
    <div class="
      u-popupResponsive
      Dialog-content
      Dialog-content--centered
      u-background-white
      u-layout-prose
      u-margin-all-xl
      u-padding-all-xl
      js-fr-dialogmodal-modal
    " aria-labelledby="modal-title">
        <div role="document" class="Prose">
            <h2 class="u-cf u-text-h2 u-borderHideFocus" id="modal-title" tabindex="0">Processo di Onboarding</h2>
            <p>
            L’<b>ingresso dei servizi all’interno del Portale "UmbriaFacile"</b> deve rispettare precisi criteri di qualità e di funzionalità (principi digital first, service design, cittadino al centro, omnicanalità, comunicazione chiara, ecc), secondo processi e metodologie ben definite.
            <br>
            Ogni <b>servizio</b>, quindi, viene <b>ridisegnato</b> nel rispetto dei <b>requisiti minimi</b> fissati per l'inserimento in catalogo: un <b>percorso impegnativo</b> per la definizione condivisa delle metodologie da seguire per l'aumento del loro livello di sofisticazione /interattività.
            <br><br>
            Ogni scheda-servizio è caratterizzata da uno <b>"stato del servizio"</b>:
            <img class="u-popupImgResponsive" src="{{ site.baseurl }}/images/2018/11/stato-del-servizio.png" alt="Stato del servizio">
            </p>
            <!--<button class="Button Button--danger js-fr-dialogmodal-close u-floatRight">Chiudi</button>-->
        </div>
    </div>
</div>
