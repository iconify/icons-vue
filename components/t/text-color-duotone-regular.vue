<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sue0rgi5i"/><path class="j1csxbc-h"/><path class="q71rf2zhu"/><path class="sqsxh9blm"/><path class="tklpoac2f"/><path class="ui32hib9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-color-duotone-regular" /></template>
<style>
.j1csxbc-h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q71rf2zhu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 20h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sqsxh9blm {
  d: path("M5 5h14");
}

.sue0rgi5i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 5h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tklpoac2f {
  d: path("M12 5v10");
}

.ui32hib9b {
  d: path("M5 20h14");
}

</style>
