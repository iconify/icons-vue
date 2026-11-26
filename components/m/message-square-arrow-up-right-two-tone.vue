<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uwjrx0j1q"/><path class="rkd0vxb4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-arrow-up-right-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rkd0vxb4k {
  d: path("M6 3L18 3C19.6569 3 21 4.3431 21 6L21 14C21 15.6569 19.6569 17 18 17L7 17L3 21L3 6C3 4.3431 4.3431 3 6 3ZM9 7H14.4994C14.7756 7 15 7.22386 15 7.5V13M9 13L14.5 7.5");
}

.uwjrx0j1q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 13.5L2 6C2 3.7908 3.7908 2 6 2L18 2C20.2092 2 22 3.7908 22 6L22 14C22 16.2092 20.2092 18 18 18L7.4142 18L3.7071 21.7071C3.5196 21.8946 3.2652 22 3 22C2.4477 22 2 21.5523 2 21Z");
  stroke: none;
}

</style>
