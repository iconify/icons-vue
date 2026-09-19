<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qto3gjtne"/><circle class="s-tu1sj_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:screenshottile" /></template>
<style>
.qto3gjtne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.5 5.5h-7c-2.2 0-4 1.8-4 4v7m37 0v-7c0-2.2-1.8-4-4-4h-7m-26 26v7c0 2.2 1.8 4 4 4h7m15 0h7c2.2 0 4-1.8 4-4v-7");
}

.s-tu1sj_i {
  cx: 24px;
  cy: 24px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
