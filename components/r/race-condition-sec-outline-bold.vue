<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iymet_cml"/><path class="z0bolwhph"/><path class="b064j7bnn"/><path class="rknmpzbdd"/><path class="iwb4l6_yp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:race-condition-sec-outline-bold" /></template>
<style>
.b064j7bnn {
  d: path("M12.5 7 15 9.5 12.5 12");
}

.iwb4l6_yp {
  d: path("m9.5 12 2.5 2.5L9.5 17");
}

.iymet_cml {
  d: path("M15.5 4H19a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V8l4 -4h3.5");
}

.rknmpzbdd {
  d: path("M5 14.5h7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z0bolwhph {
  d: path("M5 9.5h10");
}

</style>
