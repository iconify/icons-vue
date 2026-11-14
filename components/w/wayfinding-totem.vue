<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v0phoeaal"/><path class="bn1axxb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wayfinding-totem" /></template>
<style>
.bn1axxb9f {
  d: path("M9.5 7h5M13 5.5L14.5 7L13 8.5m1.5 5h-5M11 12l-1.5 1.5L11 15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0phoeaal {
  d: path("M6.5 2.5h11v19h-11Zm-3 19h17");
}

</style>
