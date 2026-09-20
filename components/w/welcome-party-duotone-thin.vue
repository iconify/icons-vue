<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y8h-esezl"/><path class="b3h8x-qqv"/><path class="ef4akx9wy"/><path class="aovjxvbkw"/><path class="fxaerfbaz"/><path class="naf5gjb6k"/><path class="e0fatccfd"/><path class="cjddu477a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:welcome-party-duotone-thin" /></template>
<style>
.aovjxvbkw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20 10 -2 2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b3h8x-qqv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 20V4h10v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cjddu477a {
  d: path("m20 10 -2 2 2 2");
}

.e0fatccfd {
  d: path("M18 12h4");
}

.ef4akx9wy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fxaerfbaz {
  d: path("M6 20V4h10v16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.naf5gjb6k {
  d: path("M12 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.y8h-esezl {
  fill: currentColor;
  d: path("M12 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
