<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gt73ribiv"/><path class="b-ufpebdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:notarize" /></template>
<style>
.b-ufpebdb {
  d: path("M8 15.5c.75-2 1.75-2 2 0c.25 1.25 1.25.75 2-.5m2.5 3a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.gt73ribiv {
  d: path("M12.8 21.5H4.5v-19h15v9.4M8 7h8m-8 3.5h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
