<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l7n7z43oo"/><path class="i5yxbkbli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:notebook-pen" /></template>
<style>
.i5yxbkbli {
  d: path("m15.121 8.464l1.415 1.415l-4.597 4.596l-1.767.353l.353-1.767Z");
}

.l7n7z43oo {
  d: path("M6 3h14v18H6ZM4 7.5h4M4 12h4m-4 4.5h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
