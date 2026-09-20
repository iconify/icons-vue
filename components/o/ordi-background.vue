<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h8g2hyk5t"/><path class="lw2s_bccd"/><path clip-rule="evenodd" class="s2jkqsbtn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ordi-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h8g2hyk5t {
  fill: var(--svg-color--fefefe, #fefefe);
  d: path("M24 0H0v24h24z");
}

.lw2s_bccd {
  fill: var(--svg-color--000, #000);
  d: path("M6.733 5.778h3.045v1.778H7.11v4.07l-.444.312v.489l.444.289v3.729h2.667v1.777H6.733l-1.4-1.777v-3.556H4V11.11h1.333V7.556zm10.534 0h-3.045v1.778h2.667v4.07l.444.312v.489l-.444.289v3.729h-2.667v1.777h3.045l1.4-1.777v-3.556H20V11.11h-1.333V7.556z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s2jkqsbtn {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M12 14.666a2.67 2.67 0 0 0 2.667-2.667a2.666 2.666 0 1 0-2.666 2.667m0-1.334a1.333 1.333 0 1 0 0-2.666a1.333 1.333 0 0 0 0 2.666");
}

</style>
