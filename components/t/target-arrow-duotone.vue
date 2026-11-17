<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j39x_ub7n"/><path class="v4ip5wjiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:target-arrow-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j39x_ub7n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 3v9h9a9 9 0 0 1-9 9a9 9 0 0 1-9-9a9 9 0 0 1 9-9");
}

.v4ip5wjiw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12a9 9 0 1 1-9-9m5 9a5 5 0 1 1-5-5m0 5l9-9m-4 0v4h4");
}

</style>
