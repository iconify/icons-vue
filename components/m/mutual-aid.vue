<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d-ekipbin"/><path class="qbu8qvtjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mutual-aid" /></template>
<style>
.d-ekipbin {
  d: path("M9.5 7h-3l-4 4L6 14.5l4.5 3.75a1.25 1.25 0 0 0 1.75-.25L18 14.5");
}

.qbu8qvtjk {
  d: path("m21.5 11l-4-4H14l-4 3.5a1.5 1.5 0 0 0 2.25 2L14 11l4 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
