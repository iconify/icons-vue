<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="srlcvibbp"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-play-off-fill" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.srlcvibbp {
  fill: currentColor;
  d: path("M20.8284 20.8284C20.0783 21.5786 19.0609 22 18 22L6 22C3.7909 22 2 20.2091 2 18L2 6C2 4.9391 2.4214 3.9217 3.1716 3.1716L8.1864 8.1864C8.0394 8.4705 7.9627 8.7857 7.9627 9.1055L7.9627 14.8945C7.9627 15.999 8.8582 16.8945 9.9627 16.8945C10.3376 16.8945 10.7049 16.7891 11.0227 16.5905L14.449 14.449ZM8.6569 2L18 2C20.2091 2 22 3.7909 22 6L22 15.3431C22 15.8954 21.5523 16.3431 21 16.3431C20.7348 16.3431 20.4804 16.2378 20.2929 16.0503L7.9497 3.7071C7.7622 3.5196 7.6569 3.2652 7.6569 3C7.6569 2.4477 8.1046 2 8.6569 2Z");
  stroke: none;
}

</style>
