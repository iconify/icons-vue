<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="htj7d_25n"/><path class="qux3mqb3d"/><path class="ljn9xlbjs"/><path class="xu9fnz9ia"/><path class="wr_ld5s1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:widget-outline-bold" /></template>
<style>
.htj7d_25n {
  d: path("M2 4a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.ljn9xlbjs {
  d: path("M17 11.5A2.5 2.5 0 0 1 19.5 9a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5 2.5 2.5 0 0 1 -2.5 -2.5");
}

.qux3mqb3d {
  d: path("M17 4.5A2.5 2.5 0 0 1 19.5 2 2.5 2.5 0 0 1 22 4.5 2.5 2.5 0 0 1 19.5 7 2.5 2.5 0 0 1 17 4.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wr_ld5s1h {
  d: path("M17 19.5a2.5 2.5 0 0 1 2.5 -2.5 2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5 2.5 2.5 0 0 1 -2.5 -2.5");
}

.xu9fnz9ia {
  d: path("M2 19.5A2.5 2.5 0 0 1 4.5 17h7a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-7A2.5 2.5 0 0 1 2 19.5");
}

</style>
