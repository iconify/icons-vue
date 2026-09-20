<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r43f98s5i"/><path class="b-11-accn"/><path class="z813dgbpy"/><path class="rxvgnomvg"/><path class="b5yjngbwf"/><path class="ql24hzbyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:streaming-response-outline-bold" /></template>
<style>
.b-11-accn {
  d: path("M5 7h10");
}

.b5yjngbwf {
  d: path("M9.5 19H13");
}

.ql24hzbyo {
  d: path("M16 19h3.5");
}

.r43f98s5i {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.rxvgnomvg {
  d: path("M3 19h3.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z813dgbpy {
  d: path("M5 11h5");
}

</style>
