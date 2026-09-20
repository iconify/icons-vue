<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tqek15bkw"/><path class="rr5s23bmj"/><path class="d1sql1bsn"/><path class="pwxki4zra"/><path class="m5ay1qb8l"/><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="acx2mjbnt"/><path class="ykj59ccld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:time-arrow-up-duotone-thin" /></template>
<style>
.acx2mjbnt {
  d: path("M12 11v6");
}

.d1sql1bsn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hk697hhuu {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jms1xqp8l {
  d: path("M9 3h6");
}

.m5ay1qb8l {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 13.5 12 11l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pwxki4zra {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rr5s23bmj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tqek15bkw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yazo7scbq {
  d: path("M12 3v3");
}

.ykj59ccld {
  d: path("M9.5 13.5 12 11l2.5 2.5");
}

</style>
