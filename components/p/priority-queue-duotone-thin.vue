<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ovzzbs_1x"/><path class="fvyu0cc4r"/><path class="hu7_04b5x"/><path class="yay79grql"/><path class="i-ifqlxrd"/><path class="zuuudpbwi"/><path class="kh31pt5af"/><path class="t99bgtbzx"/><path class="ecismzb4h"/><path class="mo-r4ib5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:priority-queue-duotone-thin" /></template>
<style>
.ecismzb4h {
  d: path("M20 15V9");
}

.fvyu0cc4r {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hu7_04b5x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i-ifqlxrd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 11 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kh31pt5af {
  d: path("M3 13h14");
}

.mo-r4ib5t {
  d: path("m18 11 2 -2 2 2");
}

.ovzzbs_1x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t99bgtbzx {
  d: path("M3 18h14");
}

.yay79grql {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 15V9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuuudpbwi {
  d: path("M3 8h14");
}

</style>
