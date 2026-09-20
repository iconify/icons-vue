<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="byyypnb5a"/><path class="d483k8bnq"/><path class="h4bl8q_qm"/><path class="ukcms4b8l"/><path class="p8x8olrmk"/><path class="vzfmp7bra"/><path class="dzjfbdtqu"/><path class="ksls36zfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:party-clean-up-duotone-regular" /></template>
<style>
.byyypnb5a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 11v9h10v-9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d483k8bnq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dzjfbdtqu {
  d: path("m6 5 3 3");
}

.h4bl8q_qm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ksls36zfl {
  d: path("m18 4 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p8x8olrmk {
  d: path("M7 11v9h10v-9");
}

.ukcms4b8l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 4 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vzfmp7bra {
  d: path("M5 11h14");
}

</style>
