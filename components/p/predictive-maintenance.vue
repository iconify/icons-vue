<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w2t8h4b5v"/><path class="kly3nbc4i"/><path class="ye2-4vbky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:predictive-maintenance" /></template>
<style>
.kly3nbc4i {
  d: path("M7 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5.5 12l3.75-3.75L18 19l3.5-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w2t8h4b5v {
  d: path("m8 4.356l.135-1.798h1.73L10 4.356l1.577.654l1.366-1.177l1.224 1.224l-1.177 1.366L13.644 8l1.798.135v1.73L13.644 10l-.654 1.577l1.177 1.366l-1.224 1.224l-1.366-1.177l-1.577.654l-.135 1.798h-1.73L8 13.644l-1.577-.654l-1.366 1.177l-1.224-1.224l1.177-1.366L4.356 10l-1.798-.135v-1.73L4.356 8l.654-1.577l-1.177-1.366l1.224-1.224L6.423 5.01Z");
}

.ye2-4vbky {
  d: path("M19 15.5h2.5V18");
}

</style>
