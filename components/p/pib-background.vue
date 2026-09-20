<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGCCKEwdyC)" class="r4i437pya"/><path class="adnydnbqp"/></g><defs><linearGradient id="SVGCCKEwdyC" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="hvlv70b8z"/><stop offset=".191" class="kb33n56ay"/><stop offset=".386" class="u1_ha7agk"/><stop offset=".579" class="srmmxjhyl"/><stop offset=".8" class="ks6404b-d"/><stop offset="1" class="acj8-9b4s"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pib-background" /></template>
<style>
.acj8-9b4s {
  stop-color: var(--svg-color--7270af, #7270af);
}

.adnydnbqp {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.778 10.428V7.596l3.177-1.808l2.449 1.406zm6-6.428L9.333 5.494l5.778 3.28V5.895zm3.778 8.729V6.132l2.666 1.458v3.7zm2.665 1.837v-2.84l-5.6 3.235l2.43 1.474zm-9.332 1.68v-2.861l5.778 3.298l-2.445 1.54zm-3.111 2.3v-5.962l2.667-1.473V20zm4.444-8.61L12 8.89l1.778 1.047v2.271L12 13.333l-1.778-1.125z");
}

.ft5dv1b6b {
  fill: none;
}

.hvlv70b8z {
  stop-color: var(--svg-color--8cb69d, #8cb69d);
}

.kb33n56ay {
  stop-color: var(--svg-color--a2c98a, #a2c98a);
}

.ks6404b-d {
  stop-color: var(--svg-color--6e7cb4, #6e7cb4);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.srmmxjhyl {
  stop-color: var(--svg-color--df6b83, #df6b83);
}

.u1_ha7agk {
  stop-color: var(--svg-color--c1a879, #c1a879);
}

</style>
