<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="az1hpy9gr"/><path class="gl3o38_gx"/><path class="lzdsnnb7v"/><path class="q3srlnbfr"/><path class="dzjr38hwz"/><path class="s74j1ubnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-turbine-outline-bold" /></template>
<style>
.az1hpy9gr {
  d: path("M12 9v12");
}

.dzjr38hwz {
  d: path("m13 9 5 5");
}

.gl3o38_gx {
  d: path("M8 21h8");
}

.lzdsnnb7v {
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.q3srlnbfr {
  d: path("M12 2v5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s74j1ubnz {
  d: path("m11 9 -5 5");
}

</style>
