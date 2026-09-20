<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b5ic9acln"/><path class="htl7tccnk"/><path class="cjspteimf"/><path class="u7rq6cbha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:similarity-euclidean-outline-thin" /></template>
<style>
.b5ic9acln {
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
}

.cjspteimf {
  d: path("M14 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htl7tccnk {
  d: path("M8 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.u7rq6cbha {
  d: path("m10 14.5 4 -4");
}

</style>
