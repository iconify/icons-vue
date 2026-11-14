<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qily9sb1s"/><path class="q_7-i3b4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:news-app" /></template>
<style>
.q_7-i3b4r {
  d: path("M9 8h6v4H9Zm0 7h6m-5.5 3h3");
}

.qily9sb1s {
  d: path("M6 2.5h12v19H6Zm4.5 2.75h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
