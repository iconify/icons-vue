<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dz366-b7c"/><path class="dlkoz2e6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tuner-sharp" /></template>
<style>
.dlkoz2e6w {
  d: path("M6.5 14a5.5 5.5 0 0 1 11 0M12 14l1.5-2.6M12 17.75v3.5m-3 0h6");
}

.dz366-b7c {
  d: path("M3.75 4.75h16.5v13H3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
