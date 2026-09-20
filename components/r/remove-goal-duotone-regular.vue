<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="djh6i29cv"/><path class="yj5kz583k"/><path class="shadeon3y"/><path class="jrr2xybsm"/><path class="hspeesv2z"/><path class="ujt25lh2u"/><path class="tv6hbrcra"/><path class="jlfjgzbqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:remove-goal-duotone-regular" /></template>
<style>
.djh6i29cv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hspeesv2z {
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
}

.jlfjgzbqx {
  d: path("M9 9h6");
}

.jrr2xybsm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.shadeon3y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.5 20.5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tv6hbrcra {
  d: path("M8.5 20.5h7");
}

.ujt25lh2u {
  d: path("M12 15v5.5");
}

.yj5kz583k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 15v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
