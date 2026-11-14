<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r0bu2pohv"/><path class="vj3axeiwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trolley-dynamics" /></template>
<style>
.r0bu2pohv {
  d: path("M2.5 6.25H14v7H2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vj3axeiwe {
  d: path("M2.75 15.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-7.25 2h19m-4.75-7.5h4.75M19.25 7.5l2.25 2.25L19.25 12");
}

</style>
