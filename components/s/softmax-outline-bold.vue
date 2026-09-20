<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jkuojibnm"/><path class="d1du4rxru"/><path class="a9cczt5un"/><path class="t3w_facee"/><path class="j4if4rbfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:softmax-outline-bold" /></template>
<style>
.a9cczt5un {
  d: path("M10 8v12");
}

.d1du4rxru {
  d: path("M6 14v6");
}

.j4if4rbfv {
  d: path("M18 14v6");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t3w_facee {
  d: path("M14 3v17");
}

</style>
