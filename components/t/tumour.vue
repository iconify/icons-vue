<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h19bvpbky"/><path class="jyid_08vz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tumour" /></template>
<style>
.h19bvpbky {
  d: path("M12 2.75c2.5-.5 4 1.25 3.75 3c2.25-.75 4.5 1 3.75 3.5c2.25 1 2.25 4.25.25 5.25c.75 2.5-1.25 4.75-3.75 4c-.75 2.5-4 3.25-5.5 1.25c-2 1.5-5 .25-4.75-2.25c-2.5-.5-3.5-3.5-1.5-5c-1.75-2-.5-5 2-5c0-2.5 2.5-4 4.5-3c.25-1 .5-1.5 1.25-1.75Z");
}

.jyid_08vz {
  d: path("M7.5 14.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM13.25 9a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
