<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fha6990wp"/><path class="hx093egei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rsvp-card-sharp" /></template>
<style>
.fha6990wp {
  d: path("M2.75 4.75h18.5v14.5H2.75z");
}

.hx093egei {
  d: path("M7 13.75h2.25v3h-3v-3zm5.75-4.25h5.5m-5.5 5.75h5.5M5.75 9.5l1.5 1.5l3-3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
