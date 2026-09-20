<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="naa67qbfw"/><path class="l4a5a5bci"/><path class="havo1zbor"/><path class="ondrk6tkv"/><path class="ppivcbbzp"/><path class="t87ohzbeq"/><path class="qjej79sen"/><path class="qd0z4jbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wait-until-duotone-bold" /></template>
<style>
.havo1zbor {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.5 12H17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l4a5a5bci {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.naa67qbfw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ondrk6tkv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 9.5 19 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ppivcbbzp {
  d: path("M5 4v16");
}

.qd0z4jbov {
  d: path("M16.5 9.5 19 12l-2.5 2.5");
}

.qjej79sen {
  d: path("M12.5 12H17");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t87ohzbeq {
  d: path("M9 4v16");
}

</style>
