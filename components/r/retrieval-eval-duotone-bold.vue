<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plw-owhdh"/><path class="yjc9h6oua"/><path class="mw2gfo1lk"/><path class="pqt5vxabu"/><path class="z8ti_fbgk"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="ymk1v8j2l"/><path class="lyy2bnbbp"/><path class="mrbwrkdfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:retrieval-eval-duotone-bold" /></template>
<style>
.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
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

.mw2gfo1lk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6.5 10 2 2L11 9.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.plw-owhdh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pqt5vxabu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 7 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yjc9h6oua {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ymk1v8j2l {
  d: path("m6.5 10 2 2L11 9.5");
}

.z8ti_fbgk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 7 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
