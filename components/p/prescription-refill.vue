<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hywzzdbmf"/><path class="h63s95onz"/><path class="jsyccuo7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:prescription-refill" /></template>
<style>
.h63s95onz {
  d: path("M6.25 16.5V9.75H8.5c1 0 1.75.75 1.75 1.75s-.75 1.75-1.75 1.75H6.25m2.25 0l3.25 3.5m0-3.25l-2.5 3.25m11.565-.375a3.25 3.25 0 1 1-3.927-1.429");
}

.hywzzdbmf {
  d: path("M12 19H3.5V6.5h11v6.6M4.5 2.5h9v4h-9Z");
}

.jsyccuo7p {
  d: path("m19.75 14.5l1 .75l-1 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
