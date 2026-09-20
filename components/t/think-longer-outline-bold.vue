<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="c8tpvpbrt"/><path class="eylqpv51p"/><path class="a5a5iacnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:think-longer-outline-bold" /></template>
<style>
.a5a5iacnl {
  d: path("M15 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.c8tpvpbrt {
  d: path("M7 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.eylqpv51p {
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hk697hhuu {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

.jms1xqp8l {
  d: path("M9 3h6");
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
