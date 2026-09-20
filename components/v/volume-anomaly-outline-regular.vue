<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vezho9b5g"/><path class="ul-6megvv"/><path class="hb39b-bug"/><path class="lqktbo2ou"/><path class="ejc7sbawl"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:volume-anomaly-outline-regular" /></template>
<style>
.ejc7sbawl {
  d: path("M20 15v4");
}

.hb39b-bug {
  d: path("M12 3v16");
}

.lqktbo2ou {
  d: path("M16 12v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ul-6megvv {
  d: path("M8 11v8");
}

.vezho9b5g {
  d: path("M4 14v5");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
