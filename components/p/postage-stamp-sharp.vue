<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="et60b1qys"/><path class="z2qsv0b2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:postage-stamp-sharp" /></template>
<style>
.et60b1qys {
  d: path("M4.25 3.25h1.19V4h1.5v-.75h2.37V4h1.5v-.75h2.38V4h1.5v-.75h2.37V4h1.5v-.75h1.19v1H19v1.5h.75v2H19v1.5h.75v2H19v1.5h.75v2H19v1.5h.75v2H19v1.5h.75v1h-1.19V20h-1.5v.75h-2.37V20h-1.5v.75h-2.38V20h-1.5v.75H6.94V20h-1.5v.75H4.25v-1H5v-1.5h-.75v-2H5v-1.5h-.75v-2H5v-1.5h-.75v-2H5v-1.5h-.75v-2H5v-1.5h-.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2qsv0b2y {
  d: path("M7.5 6.5h9V15h-9zm1 11.25h7");
}

</style>
