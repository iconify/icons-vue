<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cqt3macfs"/><path class="h7zwju-ro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tote-bag-printed" /></template>
<style>
.cqt3macfs {
  d: path("M3.5 10.5h17l-1 11h-15Zm3 0c0-8 7.5-8 7.5 0");
}

.h7zwju-ro {
  d: path("M10 10.5c0-8 7.5-8 7.5 0M12 13l.882 2.036l2.209.21l-1.664 1.468l.483 2.165L12 17.75l-1.91 1.129l.483-2.165l-1.664-1.468l2.209-.21Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
