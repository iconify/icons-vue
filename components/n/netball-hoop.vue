<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l641au4zo"/><path class="om0-80bys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:netball-hoop" /></template>
<style>
.l641au4zo {
  d: path("M6.25 3v18m-2.5 0h5M6.25 7h4m0 0a5 1.75 0 1 0 10 0a5 1.75 0 1 0-10 0Z");
}

.om0-80bys {
  d: path("m12.75 8.5l1 6.5h3l1-6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
