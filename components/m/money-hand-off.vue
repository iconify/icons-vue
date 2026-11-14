<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k2efi6eva"/><path class="tjgkq0b1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:money-hand-off" /></template>
<style>
.k2efi6eva {
  d: path("M12.2 16.5H2.5v-12h18v8.8");
}

.tjgkq0b1e {
  d: path("M8.5 10.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm6.5 7.75h6.5m-2.75-2.75l2.75 2.75L18.75 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
