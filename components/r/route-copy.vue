<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bf5r6ebfy"/><path class="qf-jp1b3x"/><path class="gv3akpzjw"/><path class="v455h9bwo"/><path class="g3ycjzbfz"/><path class="spt_yibok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:route-copy" /></template>
<style>
.bf5r6ebfy {
  d: path("M3.5 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.g3ycjzbfz {
  d: path("M14 16v-5c0-3 4-3 4-6");
}

.gv3akpzjw {
  fill: currentColor;
  d: path("M8.5 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.qf-jp1b3x {
  d: path("M6 16v-5c0-3 4-3 4-6");
}

.spt_yibok {
  fill: currentColor;
  d: path("M16.5 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v455h9bwo {
  d: path("M11.5 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
