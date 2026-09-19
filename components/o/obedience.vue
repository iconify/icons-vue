<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="kiig5cc1i"/><path class="t7svcmlez"/><path class="whkis1brj"/><circle class="ok0qm9l4u"/><path class="ugg2vsbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:obedience" /></template>
<style>
.kiig5cc1i {
  cx: 24px;
  cy: 17.767px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.5px;
  ry: 7.973px;
}

.ok0qm9l4u {
  cx: 24.194px;
  cy: 33.895px;
  r: 4.311px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t7svcmlez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.03 20.807c-2.924-2.895-9.895-4.931-18.03-4.931S8.893 17.913 5.969 20.807");
}

.ugg2vsbba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.194 30.268v-1.369");
}

.whkis1brj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 17.767v7.422c0 4.403 8.73 7.973 19.5 7.973s19.5-3.57 19.5-7.973v-7.422");
}

</style>
