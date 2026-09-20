<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ho3rbobyv"/><path class="fk9yoacub"/><path class="w7xlhi5uw"/><path class="jw3oso0og"/><path class="mi_rhabsp"/><path class="pm0e7ny3b"/><path class="tbo01n9ke"/><path class="s88iiwf1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:villa-duotone-regular" /></template>
<style>
.fk9yoacub {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 11v8h8v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ho3rbobyv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 11 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jw3oso0og {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 19 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mi_rhabsp {
  d: path("m2 11 6 -6 6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pm0e7ny3b {
  d: path("M4 11v8h8v-8");
}

.s88iiwf1g {
  d: path("m15 19 2 -2 2 2 2 -2");
}

.tbo01n9ke {
  d: path("m15 14 2 -2 2 2 2 -2");
}

.w7xlhi5uw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 14 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
