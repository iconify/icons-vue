<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="vb0yblbln"/><rect class="pxgwcfb3y"/><path class="yiykff0bi"/><rect class="fthz0ytum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobilfox" /></template>
<style>
.fthz0ytum {
  width: 4.834px;
  height: 7.297px;
  x: 20.99px;
  y: 25.056px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.417px;
  ry: 2.417px;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.pxgwcfb3y {
  width: 4.834px;
  height: 7.297px;
  x: 18.874px;
  y: 15.648px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.417px;
  ry: 2.417px;
}

.vb0yblbln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.852 15.648v7.296H38.5m-5.752-7.296v7.296M9.5 22.936v-7.288l3.648 7.296l3.649-7.285v7.285m11.849-3.648a1.824 1.824 0 0 1 0 3.648h-3.01v-7.297h3.01a1.824 1.824 0 0 1 0 3.649m0 0h-3.01");
}

.yiykff0bi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.96 25.056l4.834 7.296m0-7.296l-4.834 7.296m-10.754-3.648h2.372m-2.372 3.648v-7.296h3.649");
}

</style>
