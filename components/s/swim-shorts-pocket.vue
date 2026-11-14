<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xa3h_bcte"/><path class="w9kdcac5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:swim-shorts-pocket" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w9kdcac5i {
  d: path("M16.5 8q.5 3.5 3 4.25");
}

.xa3h_bcte {
  d: path("M4 4.5h16V8H4ZM5 8L3.75 19.5h6.75l1.5-6l1.5 6h6.75L19 8m-7 0l-1.25 2.75M12 8l1.25 2.75");
}

</style>
