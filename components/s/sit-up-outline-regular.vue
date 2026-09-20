<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="neabk9byu"/><path class="ctc9ejfah"/><path class="ycakidrmo"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sit-up-outline-regular" /></template>
<style>
.bod4n0b3z {
  d: path("M2 18h20");
}

.ctc9ejfah {
  d: path("m8 10 5 5");
}

.neabk9byu {
  d: path("M2 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ycakidrmo {
  d: path("m13 15 4 -4 4 4");
}

</style>
