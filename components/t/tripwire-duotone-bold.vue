<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p7air0nan"/><path class="e7h5h_hse"/><path class="yfkrqybdn"/><path class="ezxgsvrsn"/><path class="qmlzdy5le"/><path class="s-etibjpa"/><path class="cwy6p7vpw"/><path class="urilmibxp"/><path class="c_jwtcbat"/><path class="v7xfanbfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tripwire-duotone-bold" /></template>
<style>
.c_jwtcbat {
  d: path("M12 3.5V6");
}

.cwy6p7vpw {
  d: path("M20 10v10");
}

.e7h5h_hse {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ezxgsvrsn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 13h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p7air0nan {
  fill: currentColor;
  d: path("M11 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qmlzdy5le {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3.5V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s-etibjpa {
  d: path("M4 10v10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.urilmibxp {
  d: path("M4 13h16");
}

.v7xfanbfw {
  d: path("M11 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.yfkrqybdn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
