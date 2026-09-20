<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGAFuik7sT)" class="r4i437pya"/><path class="axby5twry"/></g><defs><linearGradient id="SVGAFuik7sT" x1="5.5" x2="18.5" y1="6" y2="19" gradientUnits="userSpaceOnUse"><stop class="l44tr8bke"/><stop offset=".18" class="b9avsib0j"/><stop offset=".38" class="n_kyw6brh"/><stop offset=".5" class="wnfur-bji"/><stop offset=".65" class="qs1040l3v"/><stop offset=".82" class="k52mwnbbf"/><stop offset="1" class="g8koxjb3i"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:qsr-background" /></template>
<style>
.axby5twry {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.98 20l-4.48-8.25L4 8.12V7.5A3.5 3.5 0 0 1 7.5 4h.52l4.48 8.25l7.5 3.515v.735a3.5 3.5 0 0 1-3.5 3.5z");
}

.b9avsib0j {
  stop-color: var(--svg-color--54bcf0, #54bcf0);
}

.ft5dv1b6b {
  fill: none;
}

.g8koxjb3i {
  stop-color: var(--svg-color--a745f4, #a745f4);
}

.k52mwnbbf {
  stop-color: var(--svg-color--51bcf4, #51bcf4);
}

.l44tr8bke {
  stop-color: var(--svg-color--a745f5, #a745f5);
}

.n_kyw6brh {
  stop-color: var(--svg-color--99e5c5, #99e5c5);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qs1040l3v {
  stop-color: var(--svg-color--91e1c8, #91e1c8);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.wnfur-bji {
  stop-color: var(--svg-color--fffcd8, #fffcd8);
}

</style>
