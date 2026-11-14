<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kq-k0mbwi"/><path class="x1uvrcbvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scale-bar" /></template>
<style>
.kq-k0mbwi {
  d: path("M2.5 11h19v4h-19Zm0-4v4M12 8v3m9.5-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1uvrcbvq {
  fill: currentColor;
  d: path("M2.5 11h4.75v4H2.5Zm9.5 0h4.75v4H12Z");
}

</style>
