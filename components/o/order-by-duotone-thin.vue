<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="q_wi_sced"/><path class="f7wvhfedz"/><path class="qps69pb2b"/><path class="k6nj2fbya"/><path class="qxnpdo0dk"/><path class="zuu1wnb1v"/><path class="o46_3ibvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:order-by-duotone-thin" /></template>
<style>
.ck7sgubpk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f7wvhfedz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 15h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.o46_3ibvz {
  d: path("M3 20h6");
}

.q_wi_sced {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 10h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qps69pb2b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qxnpdo0dk {
  d: path("M3 10h14");
}

.zuu1wnb1v {
  d: path("M3 15h10");
}

</style>
