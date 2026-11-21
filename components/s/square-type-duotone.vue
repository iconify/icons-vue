<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uurgnvu9t"/><path class="dx-zqfqtn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-type-duotone" /></template>
<style>
.dx-zqfqtn {
  d: path("M7 9V8C7 7.4477 7.4477 7 8 7H16C16.5523 7 17 7.4477 17 8V9M12 7V17M9.5 17H14.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uurgnvu9t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2L18 2C20.2092 2 22 3.7908 22 6L22 18C22 20.2092 20.2092 22 18 22L6 22C3.7908 22 2 20.2092 2 18L2 6C2 3.7908 3.7908 2 6 2Z");
  stroke: none;
}

</style>
