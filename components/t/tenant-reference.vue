<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jola0laqq"/><path class="ghyisybjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tenant-reference" /></template>
<style>
.ghyisybjc {
  d: path("m3.5 6l8.5 6.25L20.5 6M15 21.5v-4h1.5l1.5-3a1 1 0 0 1 1.5.75V17H21a.75.75 0 0 1 .75.75L21 21a.75.75 0 0 1-.75.5Zm1.5-4v4");
}

.jola0laqq {
  d: path("M12.2 19H2.5V4.5h19V13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
