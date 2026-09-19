<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dlhb5kbqq"/><circle class="lr7kxmqai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:presencepublisher" /></template>
<style>
.dlhb5kbqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 21.06v-3.63m14.72 10.06A15.68 15.68 0 0 0 30 18.34m13.5 7.43a20.74 20.74 0 0 0-14.76-13.16M9.28 27.49A15.68 15.68 0 0 1 18 18.34M4.5 25.77a20.74 20.74 0 0 1 14.76-13.16m4.74 0l1.79 4.58h-3.56z");
}

.lr7kxmqai {
  cx: 24px;
  cy: 30.56px;
  r: 4.84px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
