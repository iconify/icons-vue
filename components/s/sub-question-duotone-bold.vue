<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="no_v-sbjp"/><path class="plw-owhdh"/><path class="yjc9h6oua"/><path class="h2k3jgbze"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="njsdrxbyk"/><path class="xlsprdnsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sub-question-duotone-bold" /></template>
<style>
.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.h2k3jgbze {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.5 8a2.5 2.5 0 1 1 2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.njsdrxbyk {
  d: path("M7.5 8a2.5 2.5 0 1 1 2.5 2.5");
}

.no_v-sbjp {
  fill: currentColor;
  d: path("M9 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
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

.xlsprdnsf {
  d: path("M9 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.yjc9h6oua {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
