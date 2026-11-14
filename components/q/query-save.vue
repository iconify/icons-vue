<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="urgoq48rs"/><path class="aq9007b2p"/><path class="e_kdbo2fp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:query-save" /></template>
<style>
.aq9007b2p {
  d: path("M7 10.5L4.5 13L7 15.5m3.5-5.5l-1.75 6m3.5-5.5l1.485 1.485M14.5 15.5a1 1 0 0 1 1-1H20l1.5 1.5v4.5a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1Z");
}

.e_kdbo2fp {
  d: path("M16.5 21.5V19h3v2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.urgoq48rs {
  d: path("M11.7 20.5H2.5v-17h19v8.6m-19-4.35h19");
}

</style>
