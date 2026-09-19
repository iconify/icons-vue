<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="z5da0ubok"/><path class="hxy511b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:securego" /></template>
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

.hxy511b1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.044 21.595h16.078v9.287c-.019.5-.455.833-1.081.833H17.218c-.734 0-1.34-.537-1.34-1.032zm.071 3.037H31.92");
}

.z5da0ubok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 39.756c1.485 0 13.402-4.995 13.402-11.938V13.865L24 10.275l-13.402 3.59v13.953c0 6.943 11.917 11.938 13.402 11.938");
}

</style>
