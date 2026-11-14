<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mx5852tgj"/><path class="d5so-_bhe"/><path class="xf0z4fqil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:orchid" /></template>
<style>
.d5so-_bhe {
  d: path("M12 11c-3-4-8-4-9-1c1 3.5 6 3.5 9 1Zm0 0c3-4 8-4 9-1c-1 3.5-6 3.5-9 1Z");
}

.mx5852tgj {
  d: path("M12 11c-2.5-3-2-6.5 0-8.5c2 2 2.5 5.5 0 8.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xf0z4fqil {
  d: path("M12 11c-4 1.5-5 6-3 9.5q3-2 6 0c2-3.5 1-8-3-9.5Z");
}

</style>
