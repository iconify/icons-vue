<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kt-_axlhq"/><path class="iulb4mb6k"/><path class="kj672_yfn"/><path class="qzwh4exzn"/><path class="wgokw4bbc"/><path class="oifr9zbpt"/><path class="x5li7lwaz"/><path class="oio7uh0en"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:metronome-duotone-regular" /></template>
<style>
.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kj672_yfn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kt-_axlhq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20c1 -7 4 -14 6 -17h4c2 3 5 10 6 17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.oio7uh0en {
  d: path("M10 11h4");
}

.qzwh4exzn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wgokw4bbc {
  d: path("M4 20c1 -7 4 -14 6 -17h4c2 3 5 10 6 17");
}

.x5li7lwaz {
  d: path("M12 7v12");
}

</style>
