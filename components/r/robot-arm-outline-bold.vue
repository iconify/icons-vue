<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o46_3ibvz"/><path class="gzh4n16ws"/><path class="b6ubinbne"/><path class="ti0atfbnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:robot-arm-outline-bold" /></template>
<style>
.b6ubinbne {
  d: path("m6 12 6 -6h8v3.5");
}

.gzh4n16ws {
  d: path("M6 12v8");
}

.o46_3ibvz {
  d: path("M3 20h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ti0atfbnf {
  d: path("M17 6v3.5");
}

</style>
