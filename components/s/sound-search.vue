<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fkzou3b6j"/><circle class="mmbi6vbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sound-search" /></template>
<style>
.fkzou3b6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.663 34.643V14.764h8.912c.815 0 1.476-.66 1.476-1.476V5.976c0-.815-.66-1.476-1.476-1.476H22.848c-.815 0-1.476.66-1.476 1.476v20.188m6.291-11.4l9.885-9.885m-9.885 9.885l-6.312-6.311");
}

.mmbi6vbhk {
  cx: 18.806px;
  cy: 34.643px;
  r: 8.857px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
