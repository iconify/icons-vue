<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="oz0mquhye"/><path class="cpkc6cxsd"/><path class="ox6gzybvn"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="u8oheccad"/><path class="mq159kbup"/><path class="m-y6zjb5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:refusal-rate-duotone-regular" /></template>
<style>
.cpkc6cxsd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m-y6zjb5q {
  d: path("M16 15v3");
}

.mq159kbup {
  d: path("M12 15v3");
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

.ox6gzybvn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oz0mquhye {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.u8oheccad {
  d: path("M8 15v3");
}

</style>
