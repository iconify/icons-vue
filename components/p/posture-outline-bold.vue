<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="crv4i00bu"/><path class="ma5mp6b8k"/><path class="wihdixnjz"/><path class="q6r-ungsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:posture-outline-bold" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.ma5mp6b8k {
  d: path("M11 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.q6r-ungsl {
  d: path("m10 19 4 -4 4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wihdixnjz {
  d: path("M14 9v6");
}

</style>
