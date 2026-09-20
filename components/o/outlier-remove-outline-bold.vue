<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="keqc2pbxm"/><path class="xcjkf-bzr"/><path class="n4avueb2x"/><path class="yzgjkacew"/><path class="szv640b_x"/><path class="v79lu9btt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:outlier-remove-outline-bold" /></template>
<style>
.keqc2pbxm {
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n4avueb2x {
  d: path("M6 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.szv640b_x {
  d: path("m16.5 9.5 4 4");
}

.v79lu9btt {
  d: path("m20.5 9.5 -4 4");
}

.xcjkf-bzr {
  d: path("M9 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.yzgjkacew {
  d: path("M16.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
