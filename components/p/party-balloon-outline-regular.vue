<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="emoq9e-ad"/><path class="c9x5rubht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:party-balloon-outline-regular" /></template>
<style>
.c9x5rubht {
  d: path("M12 16c0 2 2 3 1 5");
}

.emoq9e-ad {
  d: path("M12 4c3.5 0 6 2.5 6 6s-2.5 6 -6 6 -6 -2.5 -6 -6 2.5 -6 6 -6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
