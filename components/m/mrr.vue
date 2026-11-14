<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cud_2obpz"/><path class="ztnv-abvf"/><path class="aispypb3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mrr" /></template>
<style>
.aispypb3t {
  d: path("m16.5 13.5l1.5 1.25L16.5 16");
}

.cud_2obpz {
  d: path("M12.5 20.5h-9V5h17v6.9M8 3v4m8-4v4M3.5 10h12.3m.8 0h3.9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ztnv-abvf {
  d: path("M12.25 12.75q-.375-.75-1.5-.75c-1 0-1.5.5-1.5 1.25c0 1.392 2.797 1.062 3.201 2.404m-.408 1.221c-.315.238-.77.375-1.293.375c-.75 0-1.5-.25-1.75-.75m1.75-5.75V12m0 5.25v1.25m10.5-.5A3.25 3.25 0 1 1 18 14.75");
}

</style>
