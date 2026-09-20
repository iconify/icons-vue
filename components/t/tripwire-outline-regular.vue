<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s-etibjpa"/><path class="cwy6p7vpw"/><path class="urilmibxp"/><path class="c_jwtcbat"/><path class="v7xfanbfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tripwire-outline-regular" /></template>
<style>
.c_jwtcbat {
  d: path("M12 3.5V6");
}

.cwy6p7vpw {
  d: path("M20 10v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s-etibjpa {
  d: path("M4 10v10");
}

.urilmibxp {
  d: path("M4 13h16");
}

.v7xfanbfw {
  d: path("M11 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
