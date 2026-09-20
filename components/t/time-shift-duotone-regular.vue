<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oa__skhab"/><path class="a-ib5crgb"/><path class="w8h2wrjnp"/><path class="g02azz8fb"/><path class="kdee3bb5f"/><path class="w9rv6acfm"/><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="lcdiu5g_w"/><path class="ikiprn9sq"/><path class="xiowoubxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:time-shift-duotone-regular" /></template>
<style>
.a-ib5crgb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g02azz8fb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hk697hhuu {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

.ikiprn9sq {
  d: path("M9 14h6");
}

.jms1xqp8l {
  d: path("M9 3h6");
}

.kdee3bb5f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 14h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lcdiu5g_w {
  d: path("M9 11v6");
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

.w9rv6acfm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.5 11.5 15 14l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xiowoubxu {
  d: path("M12.5 11.5 15 14l-2.5 2.5");
}

.yazo7scbq {
  d: path("M12 3v3");
}

</style>
