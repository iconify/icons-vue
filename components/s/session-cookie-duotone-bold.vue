<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uyhyoc4ot"/><path class="gf0hswvuq"/><path class="f2vxqlbwm"/><path class="n7t0anb5n"/><path class="wqh892bhx"/><path class="u84sg0ngq"/><path class="wvuc0ff5n"/><path class="y6kfzfgng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:session-cookie-duotone-bold" /></template>
<style>
.f2vxqlbwm {
  fill: currentColor;
  d: path("M10 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gf0hswvuq {
  fill: currentColor;
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n7t0anb5n {
  fill: currentColor;
  d: path("M14 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u84sg0ngq {
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.uyhyoc4ot {
  fill: currentColor;
  d: path("M12 4a8 8 0 1 0 8 8 6 6 0 0 1 -8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wqh892bhx {
  d: path("M12 4a8 8 0 1 0 8 8 6 6 0 0 1 -8 -8");
}

.wvuc0ff5n {
  d: path("M10 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.y6kfzfgng {
  d: path("M14 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
