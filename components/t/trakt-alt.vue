<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="d9olisb_u"/><path class="p9cs7gxnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trakt-alt" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d9olisb_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.904 4.433L8.141 29.121zm6.331 34.737L18.699 18.638zM32.757 8.637L22.441 18.979zm.448 3.609l-8.858 8.915zM8.64 32.764l10.034-10.065l18.178 18.178");
}

.p9cs7gxnr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.804 37.657l10.932-10.932L34.313 42.55");
}

</style>
