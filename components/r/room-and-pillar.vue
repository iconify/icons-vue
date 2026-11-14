<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kbj17nbpa"/><path class="xrcwi4b2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:room-and-pillar" /></template>
<style>
.kbj17nbpa {
  d: path("M9.5 2h5v5h-5ZM2 9.5h5v5H2Zm15 0h5v5h-5ZM9.5 17h5v5h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xrcwi4b2h {
  fill: currentColor;
  d: path("M2.75 2.75h3.5v3.5h-3.5Zm15 0h3.5v3.5h-3.5Zm-7.5 7.5h3.5v3.5h-3.5Zm-7.5 7.5h3.5v3.5h-3.5Zm15 0h3.5v3.5h-3.5Z");
}

</style>
