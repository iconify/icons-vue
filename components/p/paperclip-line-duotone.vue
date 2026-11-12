<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f0pgunbkn"/><path class="mcvml3m6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-line-duotone" /></template>
<style>
.f0pgunbkn {
  d: path("M7.9175 17.8068L15.8084 10.2535C16.7558 9.34668 16.7558 7.87637 15.8084 6.96951M3 10.0346L9.40419 3.90441C12.0569 1.3652 16.3578 1.3652 19.0105 3.90441");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mcvml3m6h {
  d: path("M15.8079 6.9694C14.8605 6.06254 13.3245 6.06253 12.3771 6.9694L4.5434 14.4679C2.74335 16.191 2.74335 18.9846 4.5434 20.7076C6.34344 22.4306 9.2619 22.4306 11.0619 20.7076L19.01 13.0996C21.6627 10.5604 21.6627 6.44351 19.01 3.9043");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
