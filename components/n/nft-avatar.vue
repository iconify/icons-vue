<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tsbyu22qc"/><path class="bqdxtvbui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nft-avatar" /></template>
<style>
.bqdxtvbui {
  d: path("M6.75 9.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm-1 10.25c0-2.75 1.5-4.5 3.75-4.5c1.485 0 2.644.763 3.26 2.072m5.74-1.822l3.25 3.25l-3.25 3.25l-3.25-3.25Z");
}

.tsbyu22qc {
  d: path("M12.3 19.5H2.5v-17h17v9.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
