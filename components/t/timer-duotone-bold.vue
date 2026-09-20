<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rq77ywb_t"/><path class="ka65bt2el"/><path class="z6iz6metx"/><path class="nu4ml-bmq"/><path class="kc811hbmp"/><path class="hk697hhuu"/><path class="gwnaabclj"/><path class="ey3upmocl"/><path class="yazo7scbq"/><path class="jms1xqp8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:timer-duotone-bold" /></template>
<style>
.ey3upmocl {
  d: path("M14 14h4");
}

.gwnaabclj {
  d: path("M12 9v5");
}

.hk697hhuu {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

.jms1xqp8l {
  d: path("M9 3h6");
}

.ka65bt2el {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v5");
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

.z6iz6metx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 14h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
