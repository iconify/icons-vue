<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kn0tcm93r"/><path class="xaitxdbcw"/><path class="brze8vkpt"/><path class="pw61xnbei"/><path class="e3ixvub0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pull-request-outline-bold" /></template>
<style>
.brze8vkpt {
  d: path("M18 5v11.5");
}

.e3ixvub0q {
  d: path("m15 8 3 -3 3 3");
}

.kn0tcm93r {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.pw61xnbei {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xaitxdbcw {
  d: path("M6 7.5V21");
}

</style>
