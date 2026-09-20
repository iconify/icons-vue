<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c30ujnbdh"/><path class="vn6-di86m"/><path class="zoz5ar7wf"/><path class="v0y09obth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pocket-money-outline-regular" /></template>
<style>
.c30ujnbdh {
  d: path("M4 3v11a8 8 0 0 0 16 0V3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v0y09obth {
  d: path("M12 12v4");
}

.vn6-di86m {
  d: path("M4 7h16");
}

.zoz5ar7wf {
  d: path("M9 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
