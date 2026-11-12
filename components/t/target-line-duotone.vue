<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gshkn9qqt"/><path class="a4a_b-0qv"/><path class="bhbk5gbng"/><path class="xgidqptam"/><path class="iumgjes7h"/><path class="bphn3ebac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:target-line-duotone" /></template>
<style>
.a4a_b-0qv {
  d: path("M2 12L5 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.bhbk5gbng {
  d: path("M19 12L22 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.bphn3ebac {
  stroke-linejoin: round;
  d: path("M12 12H10M12 12H14M12 12V14M12 12L12 10");
}

.gshkn9qqt {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iumgjes7h {
  d: path("M12 5L12 2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xgidqptam {
  d: path("M12 22L12 19");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
