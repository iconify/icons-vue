<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zfp8_lbwb"/><path class="ke9-pu6gt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-call-group-sharp" /></template>
<style>
.ke9-pu6gt {
  d: path("M6.75 8.5a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5Zm4.5 0a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5Zm-6.5 6.25v-2h4v2m.5 0v-2h4v2m2-4.5l4.4-2.45l1.6-1.2v10.8l-1.6-1.2l-4.4-2.45Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zfp8_lbwb {
  d: path("M2.75 6.25h12.5v11.5H2.75z");
}

</style>
