<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h8g2hyk5t"/><path class="f_h_wwb3c"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nals-background" /></template>
<style>
.f_h_wwb3c {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.733 5.777h3.045v1.778H7.11v4.071l-.444.311v.49l.444.288v3.729h2.667v1.778H6.733l-1.4-1.778v-3.556H4v-1.777h1.333V7.555zm10.534 0h-3.045v1.778h2.667v4.071l.444.311v.49l-.444.288v3.729h-2.667v1.778h3.045l1.4-1.778v-3.556H20v-1.777h-1.333V7.555zm-5.711 4.418c.213-.2.489-.418 1.03-.418c.947 0 1.636.876 1.636 1.787v2.658H12.89v-2.76c-.036-.258-.156-.796-.596-.796c-.315 0-.737.445-.737.702v2.854h-1.334V9.777h1.334z");
}

.ft5dv1b6b {
  fill: none;
}

.h8g2hyk5t {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
