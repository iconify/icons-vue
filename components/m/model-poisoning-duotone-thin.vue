<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="em15p-b6o"/><path class="lzbti609i"/><path class="q3srlnbfr"/><path class="z55i2tbmp"/><path class="mb7g-z76v"/><path class="avnm-g99q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-poisoning-duotone-thin" /></template>
<style>
.avnm-g99q {
  d: path("m14 12 -4 4");
}

.em15p-b6o {
  fill: currentColor;
  d: path("M14 8h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3v-6l3 -3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lzbti609i {
  d: path("M14 8h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3v-6l3 -3h3");
}

.mb7g-z76v {
  d: path("m10 12 4 4");
}

.q3srlnbfr {
  d: path("M12 2v5");
}

.z55i2tbmp {
  d: path("m9 4 3 3 3 -3");
}

</style>
