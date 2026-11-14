<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fgqqg8b1s"/><path class="fdnhv03xq"/><path class="altju86mk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-scooter" /></template>
<style>
.altju86mk {
  d: path("M7.5 14a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm6.5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.fdnhv03xq {
  d: path("M8.75 12.75h6.5L14 7.25m-1.5 0h2.75");
}

.fgqqg8b1s {
  d: path("M12 21.5C9 19 3.5 15 3.5 11a8.5 8.5 0 0 1 17 0c0 4-5.5 8-8.5 10.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
