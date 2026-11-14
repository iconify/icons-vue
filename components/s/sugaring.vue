<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tp82afbkj"/><path class="lll-ambyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sugaring" /></template>
<style>
.lll-ambyz {
  d: path("M12.5 11.5s1.75 2.25 1.75 3.5a1.75 1.75 0 0 1-3.5 0c0-1.25 1.75-3.5 1.75-3.5Z");
}

.tp82afbkj {
  d: path("M3.5 12H5v7a2.5 2.5 0 0 0 2.5 2.5h9A2.5 2.5 0 0 0 19 19v-7h1.5M17.268 1.611l2.121 2.121l-5.657 5.657l-2.121-2.121Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
