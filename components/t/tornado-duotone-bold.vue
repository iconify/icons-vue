<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aqn8oeb4o"/><path class="l9xdtdboa"/><path class="um18atgqz"/><path class="b3yi30b7t"/><path class="jt4cmkb9l"/><path class="mg7aqnbsf"/><path class="mlhk78k2d"/><path class="l0v-b4kbr"/><path class="wy2n5sbyh"/><path class="b__1sjw6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tornado-duotone-bold" /></template>
<style>
.aqn8oeb4o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b__1sjw6v {
  d: path("m11 18 2 2");
}

.b3yi30b7t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jt4cmkb9l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m11 18 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.l9xdtdboa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.mlhk78k2d {
  d: path("M5 8h14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.um18atgqz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wy2n5sbyh {
  d: path("M10 16h4");
}

</style>
