<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f92_fnqbg"/><path class="mhur1hbyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rewind-duotone" /></template>
<style>
.f92_fnqbg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m3.744 10.704l6-3.5A1.5 1.5 0 0 1 12 8.5v7a1.5 1.5 0 0 1-2.256 1.296l-6-3.5a1.5 1.5 0 0 1 0-2.592m9 0l6-3.5A1.5 1.5 0 0 1 21 8.5v7a1.5 1.5 0 0 1-2.256 1.296l-6-3.5a1.5 1.5 0 0 1 0-2.592");
}

.ft5dv1b6b {
  fill: none;
}

.mhur1hbyo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m18.744 7.204l-6 3.5a1.5 1.5 0 0 0 0 2.592l6 3.5A1.5 1.5 0 0 0 21 15.5v-7a1.5 1.5 0 0 0-2.256-1.296m-9 0l-6 3.5a1.5 1.5 0 0 0 0 2.592l6 3.5A1.5 1.5 0 0 0 12 15.5v-7a1.5 1.5 0 0 0-2.256-1.296");
}

</style>
