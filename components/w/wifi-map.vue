<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="g7hwrxbut"/><path class="o-uzavb8z"/><path class="bu5i9f7ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wifi-map" /></template>
<style>
.bu5i9f7ag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.236 22.929a16.118 16.118 0 0 1 27.528 0");
}

.g7hwrxbut {
  cx: 24px;
  cy: 28.154px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.03px;
  ry: 3.105px;
}

.o-uzavb8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 20.609a7.6 7.6 0 0 0-7.093 5.766a10.1 10.1 0 0 0-.106 3.034c.488 4.06 4.223 7.83 7.199 11.001c2.977-3.172 6.711-6.942 7.2-11a10.1 10.1 0 0 0-.107-3.035A7.6 7.6 0 0 0 24 20.609M4.5 17.85a23.663 23.663 0 0 1 39-.004");
}

</style>
