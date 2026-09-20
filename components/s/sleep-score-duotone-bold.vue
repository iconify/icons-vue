<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d4-4pac7y"/><path class="v105zmblb"/><path class="o-slvjo4a"/><path class="myjbv3u_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sleep-score-duotone-bold" /></template>
<style>
.d4-4pac7y {
  fill: currentColor;
  d: path("M15 3a9 9 0 1 0 0 18 7 7 0 0 1 0 -18");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.myjbv3u_w {
  d: path("M22 10v10");
}

.o-slvjo4a {
  d: path("M19 14v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v105zmblb {
  d: path("M15 3a9 9 0 1 0 0 18 7 7 0 0 1 0 -18");
}

</style>
