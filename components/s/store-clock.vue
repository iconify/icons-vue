<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sna-v8b8p"/><path class="kyezsdids"/><path class="wti3g3byz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:store-clock" /></template>
<style>
.kyezsdids {
  d: path("M4.5 9.5v11h6.9m8.1-9.5V9.5m-6 8a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.sna-v8b8p {
  d: path("m3 7l1.5-4.5h15L21 7a3 3 0 0 1-6 0a3 3 0 0 1-6 0a3 3 0 0 1-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wti3g3byz {
  d: path("M17.5 15.5v2l1.5 1");
}

</style>
