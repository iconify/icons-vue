<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rq77ywb_t"/><path class="nu4ml-bmq"/><path class="kc811hbmp"/><path class="jqzsg-dka"/><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="rmc5gnimv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:retry-after-duotone-bold" /></template>
<style>
.hk697hhuu {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

.jms1xqp8l {
  d: path("M9 3h6");
}

.jqzsg-dka {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10.5 11 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kc811hbmp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nu4ml-bmq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rmc5gnimv {
  d: path("m10.5 11 3 3 -3 3");
}

.rq77ywb_t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yazo7scbq {
  d: path("M12 3v3");
}

</style>
