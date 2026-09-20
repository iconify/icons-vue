<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tqek15bkw"/><path class="kekemsbcz"/><path class="voblmpt_e"/><path class="rr5s23bmj"/><path class="d1sql1bsn"/><path class="hk697hhuu"/><path class="gwnaabclj"/><path class="ey3upmocl"/><path class="yazo7scbq"/><path class="jms1xqp8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:timer-duotone-thin" /></template>
<style>
.d1sql1bsn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ey3upmocl {
  d: path("M14 14h4");
}

.gwnaabclj {
  d: path("M12 9v5");
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

.kekemsbcz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9v5");
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

.voblmpt_e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 14h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yazo7scbq {
  d: path("M12 3v3");
}

</style>
