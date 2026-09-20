<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uvrxvrzpu"/><path class="o8zcug1ct"/><path class="jelyk0_mp"/><path class="b64bcebht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:motorbike-outline-regular" /></template>
<style>
.b64bcebht {
  d: path("m9.5 11 3 -3h4");
}

.jelyk0_mp {
  d: path("M5.5 14.5 9 11h6l3.5 3.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8zcug1ct {
  d: path("M15 14.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.uvrxvrzpu {
  d: path("M2 14.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

</style>
