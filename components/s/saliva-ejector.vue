<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nl9a5kule"/><path class="kq-6mzbxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:saliva-ejector" /></template>
<style>
.kq-6mzbxx {
  d: path("M15.87 13h-3.12l.75-2.5h2l.658 2.193M18.5 14.25L16 17a2.75 2.75 0 1 0 5 0Z");
}

.nl9a5kule {
  d: path("M4 21.5v-13a5.25 5.25 0 0 1 10.5 0v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
