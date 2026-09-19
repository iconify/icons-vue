<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="cpk0fnbgt"/><path class="px9cs0bhd"/><path class="c4ahiftcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opal-travel" /></template>
<style>
.c4ahiftcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.423 16.544c-6.196-6.168-14.608-8.72-22.66-7.713c-.971 8.055 1.619 16.456 7.814 22.625c6.195 6.168 14.608 8.72 22.66 7.713c.97-8.055-1.619-16.456-7.814-22.625");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.px9cs0bhd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.544 16.577c-6.168 6.196-8.72 14.608-7.713 22.66c8.055.971 16.456-1.619 22.625-7.814c6.168-6.196 8.72-14.608 7.713-22.66c-8.055-.97-16.456 1.619-22.625 7.814");
}

</style>
