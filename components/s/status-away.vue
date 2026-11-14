<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="flos5eqbe"/><path class="r-rpwbb5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:status-away" /></template>
<style>
.flos5eqbe {
  d: path("M12.828 21.464a9.5 9.5 0 1 1 8.636-8.636");
}

.r-rpwbb5u {
  d: path("M17.75 15A3 3 0 1 0 21 18.25A2.5 2.5 0 0 1 17.75 15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
