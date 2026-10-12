<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q52ja5b0y"/><path class="zw2p2owas"/><path class="mh0k4jbwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sticky-pad-sharp" /></template>
<style>
.mh0k4jbwa {
  d: path("M11.75 16.25v-4.5h4.5ZM6.25 7h6.5m-6.5 3.25h4");
}

.q52ja5b0y {
  d: path("M16.25 7.75h5v13.5H7.75v-5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zw2p2owas {
  d: path("M4.75 2.75h11.5v9l-4.5 4.5h-9V2.75z");
}

</style>
