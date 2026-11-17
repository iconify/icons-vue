<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q-smmxnad"/><path class="ldb3t2win"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:snowflake-off-duocolor-sharp" /></template>
<style>
.ldb3t2win {
  d: path("M12 7.5V3m2.536 7.536L19.794 7.5M12 14v7m-1.268-8.268L4.206 16.5m3.062-7.232L4.206 7.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q-smmxnad {
  stroke-opacity: 0.4;
  d: path("m12 7.5l-2-2m2 2l2-2m1.897 4.25l.732-2.732m-.732 2.732l2.732.732M12 16.5l2 2m-2-2l-2 2m-1.897-4.25l-.732 2.732m.732-2.732l-2.732-.732m2.454-3.693l-2.454.657M2 4l18 18");
}

</style>
