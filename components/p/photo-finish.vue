<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ivsj0tb_f"/><path class="cfpb273xy"/><path class="p6iqshu0r"/><path class="ry2wt-2iv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:photo-finish" /></template>
<style>
.cfpb273xy {
  fill: currentColor;
  d: path("M3 3h6v4H3V3m10.4 8H9V7h6v3.9");
}

.ivsj0tb_f {
  d: path("M3 21.5V3h12v7.9m-1.6.1H3");
}

.p6iqshu0r {
  d: path("M13.5 15H22v6.5h-8.5Zm2.75 0v-1.25h3V15");
}

.ry2wt-2iv {
  d: path("M16.25 18.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
