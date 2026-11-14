<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gf9c3vb7u"/><path class="b_1_u9b9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:raffle-ticket" /></template>
<style>
.b_1_u9b9g {
  d: path("m9.5 8.75l.882 2.036l2.209.21l-1.664 1.468l.483 2.165L9.5 13.5l-1.91 1.129l.483-2.165l-1.664-1.468l2.209-.21Z");
}

.gf9c3vb7u {
  d: path("M3 7a1.5 1.5 0 0 1 1.5-1.5h15A1.5 1.5 0 0 1 21 7v2.5a2.5 2.5 0 0 0 0 5V17a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 17v-2.5a2.5 2.5 0 0 0 0-5Zm13 1.5h.01M16 12h.01M16 15.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
