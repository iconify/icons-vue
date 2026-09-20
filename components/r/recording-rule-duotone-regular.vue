<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="boih2gbbw"/><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="udnpiibsz"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="j5573l00j"/><path class="nwoj8248o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:recording-rule-duotone-regular" /></template>
<style>
.boih2gbbw {
  fill: currentColor;
  d: path("M15.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j5573l00j {
  d: path("m7 15 3 -3h3.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nwoj8248o {
  d: path("M15.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.udnpiibsz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 15 3 -3h3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
