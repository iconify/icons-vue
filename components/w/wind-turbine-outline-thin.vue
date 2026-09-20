<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="az1hpy9gr"/><path class="gl3o38_gx"/><path class="lzdsnnb7v"/><path class="q3srlnbfr"/><path class="dzjr38hwz"/><path class="s74j1ubnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-turbine-outline-thin" /></template>
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

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lzdsnnb7v {
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.q3srlnbfr {
  d: path("M12 2v5");
}

.s74j1ubnz {
  d: path("m11 9 -5 5");
}

</style>
