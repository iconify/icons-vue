<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ludn23bxj"/><path class="ghgh84kkr"/><path class="irk9zbcmx"/><path class="qfv55ybqd"/><path class="a78831x8h"/><path class="lg40ofb3n"/><path class="l517yxbln"/><path class="rzfubwb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quic-duotone-regular" /></template>
<style>
.a78831x8h {
  d: path("M2 5h6l4 4");
}

.ghgh84kkr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h6l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.irk9zbcmx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l517yxbln {
  d: path("M12 9v6");
}

.lg40ofb3n {
  d: path("M2 19h6l4 -4");
}

.ludn23bxj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 5h6l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qfv55ybqd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rzfubwb2e {
  d: path("M12 12h10");
}

</style>
