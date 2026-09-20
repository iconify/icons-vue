<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lmj_kj__f"/><path class="oy_r10b4z"/><path class="yzilgtbzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ocean-outline-bold" /></template>
<style>
.lmj_kj__f {
  d: path("m3 8 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

.oy_r10b4z {
  d: path("m3 14 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yzilgtbzd {
  d: path("m3 20 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>
