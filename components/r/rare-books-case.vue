<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zvgo3xp1c"/><path class="lieytcc0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rare-books-case" /></template>
<style>
.lieytcc0e {
  d: path("M5.25 11.5v-6H8.5v6m0-4.25h3v4.25m0-6h2.75v6m-9 8.5v-5.75H8.5V20m0-4.25h1.2m1.8 1.7V20m6.25-6l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zvgo3xp1c {
  d: path("M12.9 20H2.5V2.5h17v8.8m-17 .2h13.4");
}

</style>
