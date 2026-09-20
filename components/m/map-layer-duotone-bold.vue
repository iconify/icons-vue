<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="woqg956gb"/><path class="kk4vcs1ji"/><path class="gumem2bkh"/><path class="ov7kkt0lo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:map-layer-duotone-bold" /></template>
<style>
.gumem2bkh {
  d: path("m6 13 6 6 6 -6");
}

.kk4vcs1ji {
  d: path("m12 2 7 7 -7 7 -7 -7Z");
}

.ov7kkt0lo {
  d: path("m8 17 4 4 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.woqg956gb {
  fill: currentColor;
  d: path("m12 2 7 7 -7 7 -7 -7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
