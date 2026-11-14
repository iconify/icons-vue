<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dj3m7n9ve"/><path class="wdzw1bb0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pharmacy-drive-thru" /></template>
<style>
.dj3m7n9ve {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v.9m-15-.9v9.5h6.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wdzw1bb0e {
  d: path("M3 9a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M6.5 20.5v-5h4v5m3.5-1v-2.25l1.75-2.5h4l2 2.5v2.25Zm2 2h.01m3.74 0h.01");
}

</style>
