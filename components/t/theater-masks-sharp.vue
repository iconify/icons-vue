<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="j-_19_btm"/><path class="teeoahg3x"/><path class="ct4jhxtfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:theater-masks-sharp" /></template>
<style>
.ct4jhxtfa {
  d: path("m14.75 13.25l1.75.75m1.75 0l1.75-.75M15.25 18l2.125-2.55L19.5 18");
}

.j-_19_btm {
  d: path("m2.75 4l3.875-1.5L10.5 4v5c0 3-1.937 5-3.875 5S2.75 12 2.75 9Z");
}

.teeoahg3x {
  d: path("m4.25 7.5l.9-1.1L6 7.5m1.25 0l.9-1.1L9 7.5m-4.5 2.75l2.125 2.55l2.125-2.55m4.75.25L17.375 9l3.875 1.5v5c0 3-1.937 5-3.875 5s-3.875-2-3.875-5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
