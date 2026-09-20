<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plw-owhdh"/><path class="yjc9h6oua"/><path class="jyq_09b0l"/><path class="s1g7vvbgv"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="cthj1cbgp"/><path class="fhw0bqmcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:step-back-prompt-duotone-bold" /></template>
<style>
.cthj1cbgp {
  d: path("M7.5 11 10 8.5l2.5 2.5");
}

.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.fhw0bqmcw {
  d: path("M7 13.5h6");
}

.jyq_09b0l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.5 11 10 8.5l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.plw-owhdh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s1g7vvbgv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 13.5h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yjc9h6oua {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
