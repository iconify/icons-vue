<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="syfvbka6q"/><path class="vi1j0zbvt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ontology-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.syfvbka6q {
  fill: var(--svg-color--49a3ff, #49a3ff);
  d: path("M24 0H0v24h24z");
}

.vi1j0zbvt {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 11.014v-6.67l13.2 13.619c-.272.23-3.568 2.934-7.488 1.73c-3.416-1.05-5.832-4.606-5.704-8.687zm15.976 2l.024 6.62L6.76 6.058c.272-.238 3.568-2.95 7.48-1.754c3.424 1.033 5.864 4.605 5.736 8.702z");
}

</style>
