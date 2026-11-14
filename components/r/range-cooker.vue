<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gnzu-uy3z"/><path class="uff-arbua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:range-cooker" /></template>
<style>
.gnzu-uy3z {
  d: path("M4 3h16v18.5H4Z");
}

.uff-arbua {
  d: path("M7 12.5h10v6H7Zm.5-5h.01m2.99 0h.01m2.99 0h.01m2.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
