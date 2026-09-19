<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-74.222 29.465 21.417)" class="aqro25brs"/><path class="a0cleabfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quillnote" /></template>
<style>
.a0cleabfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.786 6.125l-8.642 30.583m-.131-21.349l4.114 7.255m-1.743 6.166l6.766-1.77m1.474-3.878H42.5m-37 0h16.939m7.938 9.372H42.5m-37 0h17.914M5.5 41.875h18.419m-2.981-5.437l2.981 5.437l5.438-2.981");
}

.aqro25brs {
  cx: 29.465px;
  cy: 21.416px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 15.89px;
  ry: 6.4px;
}

</style>
