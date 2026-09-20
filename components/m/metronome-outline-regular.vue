<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wgokw4bbc"/><path class="oifr9zbpt"/><path class="x5li7lwaz"/><path class="oio7uh0en"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:metronome-outline-regular" /></template>
<style>
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

.wgokw4bbc {
  d: path("M4 20c1 -7 4 -14 6 -17h4c2 3 5 10 6 17");
}

.x5li7lwaz {
  d: path("M12 7v12");
}

</style>
