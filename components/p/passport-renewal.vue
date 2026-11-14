<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n0seikgpq"/><path class="o526cq8lq"/><path class="is8nqnbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:passport-renewal" /></template>
<style>
.is8nqnbzt {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

.n0seikgpq {
  d: path("M13.3 21.5H4.5v-19h15v10.4M8.5 2.5v19m3-14.5h4");
}

.o526cq8lq {
  d: path("M20.75 18.5A2.75 2.75 0 1 1 18 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
