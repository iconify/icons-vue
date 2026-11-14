<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z6gz_fg4o"/><path class="vecisnbyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:online-therapy" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vecisnbyx {
  d: path("M10.25 8.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM8 15.5c0-1.921 1.614-2.689 3.735-2.746M15 14h5a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-1.5l-3 1.75V19H15a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1Z");
}

.z6gz_fg4o {
  d: path("M11.2 15.5H4.5v-11h15v6.7m-17 7.3h8.7");
}

</style>
