<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kb4l5groh"/><path class="ojog0pl-o"/><path class="cnmf01b6n"/><path class="ib1xdrbch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medical-waste-bin" /></template>
<style>
.cnmf01b6n {
  d: path("M14.25 18a1.75 1.75 0 1 1 1.25-2.25A1.25 1.25 0 0 0 14.25 18Z");
}

.ib1xdrbch {
  d: path("M8.5 15.75A1.75 1.75 0 1 1 9.75 18a1.25 1.25 0 0 0-1.25-2.25Z");
}

.kb4l5groh {
  d: path("M5 10.5h14v11H5Zm-.5 0h15L18.25 7L6 8.5ZM9.75 9l4.5-.5");
}

.ojog0pl-o {
  d: path("m16.41 2.235l2.048 1.434l-2.868 4.096l-2.048-1.434ZM13.75 8l-1 1.5m.75 3.5a1.75 1.75 0 1 1-3 0a1.25 1.25 0 0 0 3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
