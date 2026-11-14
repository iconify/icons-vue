<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tru_4tbvs"/><path class="kxe-0xpcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:toilet-flush" /></template>
<style>
.kxe-0xpcz {
  d: path("M13.25 2.5h2.25v2.25");
}

.tru_4tbvs {
  d: path("M3.5 3H9v8H3.5Zm0 8h17c0 3.5-2.5 6-6.25 6.25L15 21H8.5l.75-4.25C5.75 16 3.5 14 3.5 11Zm15-5.5A3 3 0 1 1 14 2.902");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
