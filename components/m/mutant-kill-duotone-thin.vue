<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy5p0_yoh"/><path class="kj_xiu02e"/><path class="a20judcsg"/><path class="e9i5dwbzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mutant-kill-duotone-thin" /></template>
<style>
.a20judcsg {
  d: path("m10.5 10.5 3 3");
}

.e9i5dwbzy {
  d: path("m10.5 13.5 3 -3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kj_xiu02e {
  d: path("m12 4 8 8 -8 8 -8 -8Z");
}

.oy5p0_yoh {
  fill: currentColor;
  d: path("m12 4 8 8 -8 8 -8 -8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
