<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dba5rjonf"/><path class="zl5hlnbpt"/><path class="pheeuwqsh"/><path class="w1y52xvec"/><path class="vad3hnt0s"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="ymk1v8j2l"/><path class="lyy2bnbbp"/><path class="mrbwrkdfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:retrieval-eval-duotone-thin" /></template>
<style>
.dba5rjonf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.lyy2bnbbp {
  d: path("m10 7 4 4");
}

.mrbwrkdfc {
  d: path("m14 7 -4 4");
}

.pheeuwqsh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6.5 10 2 2L11 9.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vad3hnt0s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 7 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w1y52xvec {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 7 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ymk1v8j2l {
  d: path("m6.5 10 2 2L11 9.5");
}

.zl5hlnbpt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
