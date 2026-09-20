<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rjt239bze"/><path class="y_0uwbqws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:snowflake-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rjt239bze {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 2v20m-8 -6 16 -8M9 6l3 3 3 -3M9 18l3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y_0uwbqws {
  d: path("M12 2v20m-8 -6 16 -8M9 6l3 3 3 -3M9 18l3 -3 3 3");
}

</style>
