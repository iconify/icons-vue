<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tu9ltcpcz"/><path class="gizcrpbsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mic-arm" /></template>
<style>
.gizcrpbsx {
  d: path("M16.5 11v2.5L5.5 10l3 11.5m-5 0h10M14 6.75h5");
}

.tu9ltcpcz {
  d: path("M14 2.5h5V11h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
