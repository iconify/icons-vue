<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jj-hsp4ck"/><rect class="buxtambmx"/><rect class="kz_723hdi"/><rect class="ov6_qixgn"/><rect class="yz4fu04-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:switched" /></template>
<style>
.buxtambmx {
  width: 27.808px;
  height: 7.811px;
  x: 12.458px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.905px;
  ry: 3.905px;
}

.jj-hsp4ck {
  width: 29.549px;
  height: 7.811px;
  x: 10.723px;
  y: 35.689px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.905px;
  ry: 3.905px;
}

.kz_723hdi {
  width: 19.409px;
  height: 7.811px;
  x: 8.988px;
  y: 12.311px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.905px;
  ry: 3.905px;
}

.ov6_qixgn {
  width: 28.502px;
  height: 7.811px;
  x: 7.729px;
  y: 20.121px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.905px;
  ry: 3.905px;
}

.yz4fu04-l {
  width: 15.845px;
  height: 7.811px;
  x: 15.375px;
  y: 27.932px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.905px;
  ry: 3.905px;
}

</style>
