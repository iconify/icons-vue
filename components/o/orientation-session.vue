<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k9h3tpb4y"/><path class="rvl6_yb2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:orientation-session" /></template>
<style>
.k9h3tpb4y {
  d: path("M10.744 18.641L8.5 18l-6 2V6l6-2l1.323.378m6.432 1.37L21.5 4v14l-6 2l-2.737-.782M8.5 4v1.1m0 11.2V18m7-1.7V20");
}

.rvl6_yb2k {
  d: path("M12 16s-3.25-3.25-3.25-6a3.25 3.25 0 0 1 6.5 0c0 2.75-3.25 6-3.25 6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
