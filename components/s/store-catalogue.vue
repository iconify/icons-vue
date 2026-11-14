<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cepg9sprn"/><path class="w1pshl58j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:store-catalogue" /></template>
<style>
.cepg9sprn {
  d: path("M12 6C9.5 4.5 6 4 2.5 4.5v15c3.5-.5 7 0 9.5 1.5c2.5-1.5 6-2 9.5-1.5v-15C18 4 14.5 4.5 12 6Zm0 0v15M5 9.5h4.5M5 13h4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w1pshl58j {
  d: path("M16 7.75h3.75v9H16l-1.5-4.5Zm.5 4.5h.01");
}

</style>
