<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wwglc5bma"/><path class="yvvwcmb6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:map-layers-sharp" /></template>
<style>
.wwglc5bma {
  d: path("m3.92 8.32l2.41-.89L7.5 7l1.17.43l2.41.89l1.17.43l1.17-.43l2.41-.89L17 7v12.5l-1.17.43l-2.41.89l-1.17.43l-1.17-.43l-2.41-.89l-1.17-.43l-1.17.43l-2.41.89l-1.17.43V8.75zM7.5 7v12.5m4.75-10.75v12.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yvvwcmb6l {
  d: path("m7 4.5l4.75-1.75L16.5 4.5l4.75-1.75v13.5l-1.75.65");
}

</style>
