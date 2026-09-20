<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nptt5bbgx"/><path class="r182r524c"/><path class="uokpg3btu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mouse-outline-regular" /></template>
<style>
.nptt5bbgx {
  d: path("M7 7a5 5 0 0 1 5 -5 5 5 0 0 1 5 5v10a5 5 0 0 1 -5 5 5 5 0 0 1 -5 -5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r182r524c {
  d: path("M7 9h10");
}

.uokpg3btu {
  d: path("M12 5v3");
}

</style>
