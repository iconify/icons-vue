<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wd-nt5ejt"/><path class="bqm7t2vzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-remote" /></template>
<style>
.bqm7t2vzt {
  d: path("M6 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 6h.01m3.99 0h.01m4.24 2.75a5.3 5.3 0 0 1 7.5 0M16 19a2.83 2.83 0 0 1 4 0m-2 2h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wd-nt5ejt {
  d: path("M12.5 19.486V20.5q0 .098-.019.195t-.057.188t-.093.173q-.054.081-.124.151t-.151.124q-.082.055-.173.093t-.188.057t-.195.019h-7q-.098 0-.195-.019t-.188-.057t-.173-.093q-.081-.054-.151-.124t-.124-.151q-.055-.082-.093-.173t-.057-.188T3.5 20.5v-17q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124q.082-.055.173-.093t.188-.057T4.5 2.5h7q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188t.019.195v11.586");
}

</style>
