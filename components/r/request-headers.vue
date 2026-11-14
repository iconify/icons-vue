<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jwy_igigo"/><path class="x774g__7g"/><path class="ncysxgfob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:request-headers" /></template>
<style>
.jwy_igigo {
  d: path("M11.6 21.5H3.5v-19H18v10.2");
}

.ncysxgfob {
  d: path("M7 12.5h7.5m-7.5 4h4.5M15 21l5.25-5.25m-4-.25h4.25v4.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x774g__7g {
  fill: currentColor;
  d: path("M6.5 5.5H15v3H6.5Z");
}

</style>
