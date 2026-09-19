<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><ellipse class="bzn8qr4qv"/><ellipse class="i0l0il_kt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oppo-community" /></template>
<style>
.bzn8qr4qv {
  cx: 24px;
  cy: 20.908px;
  rx: 18.5px;
  ry: 14.263px;
}

.i0l0il_kt {
  cx: 24px;
  cy: 27.092px;
  rx: 18.5px;
  ry: 14.263px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
