<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be306ynmy"/><path class="emm04ib2w"/><path class="noimmwhne"/><path class="xgrfb-bqu"/><path class="wwnbqi33p"/><path class="nu1_4q-9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:subtask-duotone-regular" /></template>
<style>
.be306ynmy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.emm04ib2w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 10v6h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.noimmwhne {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 16h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nu1_4q-9l {
  d: path("M14 16h7");
}

.wwnbqi33p {
  d: path("M6 10v6h5");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
