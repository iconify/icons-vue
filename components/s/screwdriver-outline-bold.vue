<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="une6cneix"/><path class="z27853bvv"/><path class="covr1fb7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:screwdriver-outline-bold" /></template>
<style>
.covr1fb7y {
  d: path("m16.5 7.5 3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.une6cneix {
  d: path("m4 17 4 -4 3 3 -4 4Z");
}

.z27853bvv {
  d: path("M9.5 14.5 18 6");
}

</style>
