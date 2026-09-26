<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kzd7r4bws"/><path class="p78u3gzyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-dashed-fill" /></template>
<style>
.kzd7r4bws {
  fill: currentColor;
  d: path("M15 2L18 2C20.2091 2 22 3.7909 22 6L22 18C22 20.2091 20.2091 22 18 22L15 22C14.4477 22 14 21.5523 14 21L14 3C14 2.4477 14.4477 2 15 2Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p78u3gzyq {
  d: path("M6 3C4.34315 3 3 4.34315 3 6M3 18C3 19.6569 4.34315 21 6 21M10 3H11M10 21H11M3 10.5V13.5");
}

</style>
