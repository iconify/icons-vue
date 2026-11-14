<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aqnzdpbxr"/><path class="vlqtoyr9h"/><path class="dufn4fbfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:zoom-reset" /></template>
<style>
.aqnzdpbxr {
  d: path("M6 11.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm8.75 3.75L18.5 19");
}

.dufn4fbfs {
  d: path("m6 2.75l2.25 1l-1 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vlqtoyr9h {
  d: path("M8.178 19.252a8.25 8.25 0 0 1 0-15.504");
}

</style>
