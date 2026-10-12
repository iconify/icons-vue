<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tjmutzypq"/><path class="zk2hdm5sk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tip-jar-sharp" /></template>
<style>
.tjmutzypq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zk2hdm5sk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 7.25H6.75v3.25m6.75-3.25h3.75v3.25m-10.5 0h10.5V12c0 1.5 2.75 1.5 2.75 3.75v5.5H4v-5.5C4 13.5 6.75 13.5 6.75 12Z");
}

</style>
