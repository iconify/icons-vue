<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mvhfu0bad"/><path class="nh2h8crka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pre-authorisation" /></template>
<style>
.mvhfu0bad {
  d: path("M12.3 19H3V2.5h13v9");
}

.nh2h8crka {
  d: path("M5.5 9.5c0-2.5 1.75-4 4-4s4 1.5 4 4Zm4 0V12c0 .75-.5 1.25-1.25 1.25S7 12.75 7 12m-1 4h5.5m2.75.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm3.5 1.5l3.75 3.75m-1.75-1.75l-1 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
