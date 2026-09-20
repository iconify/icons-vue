<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="inzw2gkjz"/><path class="oa__skhab"/><path class="a-ib5crgb"/><path class="w8h2wrjnp"/><path class="jcigmbc2x"/><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="n-fiqpbfy"/><path class="jlojnsdlu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:time-alert-duotone-regular" /></template>
<style>
.a-ib5crgb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hk697hhuu {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

.inzw2gkjz {
  fill: currentColor;
  d: path("M11 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jcigmbc2x {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 10v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jlojnsdlu {
  d: path("M11 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.jms1xqp8l {
  d: path("M9 3h6");
}

.n-fiqpbfy {
  d: path("M12 10v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oa__skhab {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w8h2wrjnp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yazo7scbq {
  d: path("M12 3v3");
}

</style>
