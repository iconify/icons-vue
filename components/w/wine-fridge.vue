<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wffwdccte"/><path class="f9xfw6bcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wine-fridge" /></template>
<style>
.f9xfw6bcw {
  d: path("M7 18.5v-6a1.75 1.75 0 0 1 3.5 0v6Zm1.75-7.75V7m4.75 11.5v-6a1.75 1.75 0 0 1 3.5 0v6Zm1.75-7.75V7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wffwdccte {
  d: path("M4 2.5h16v19H4Z");
}

</style>
