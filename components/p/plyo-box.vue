<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kd-yu0b6r"/><path class="a95nfqbqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plyo-box" /></template>
<style>
.a95nfqbqv {
  d: path("M3.5 9.5H16L20.5 5M16 9.5v11M7.5 14H12");
}

.kd-yu0b6r {
  d: path("M3.5 9.5L8 5h12.5v11L16 20.5H3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
