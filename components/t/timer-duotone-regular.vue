<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oa__skhab"/><path class="ewwz7eo0r"/><path class="aq9dbzjms"/><path class="a-ib5crgb"/><path class="w8h2wrjnp"/><path class="hk697hhuu"/><path class="gwnaabclj"/><path class="ey3upmocl"/><path class="yazo7scbq"/><path class="jms1xqp8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:timer-duotone-regular" /></template>
<style>
.a-ib5crgb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.aq9dbzjms {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 14h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ewwz7eo0r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9v5");
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

.jms1xqp8l {
  d: path("M9 3h6");
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
