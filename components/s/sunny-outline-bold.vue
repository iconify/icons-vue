<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jf_v1slmw"/><path class="pg-wrtbze"/><path class="p14ag28op"/><path class="e8rvqbc4z"/><path class="yy262cc0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sunny-outline-bold" /></template>
<style>
.e8rvqbc4z {
  d: path("m4 20 3 -3");
}

.jf_v1slmw {
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0 5.5 5.5 0 1 0 -11 0");
}

.p14ag28op {
  d: path("m20 4 -3 3");
}

.pg-wrtbze {
  d: path("m4 4 3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yy262cc0h {
  d: path("m20 20 -3 -3");
}

</style>
