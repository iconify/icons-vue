<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zzv0x1bfk"/><path class="dznq1cc4f"/><rect class="t-dywz-jr"/><rect class="n9zkzcjlw"/><path class="z3kfpccec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:volvo-cars" /></template>
<style>
.dznq1cc4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.754 20.743l-2.877 6.514L7 20.743");
}

.n9zkzcjlw {
  width: 5.429px;
  height: 6.514px;
  x: 35.571px;
  y: 20.743px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.714px;
  ry: 2.714px;
}

.t-dywz-jr {
  width: 5.429px;
  height: 6.514px;
  x: 14.839px;
  y: 20.743px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.714px;
  ry: 2.714px;
}

.z3kfpccec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.486 20.743l-2.878 6.514l-2.877-6.514m-4.579 0v6.514h4.343");
}

.zzv0x1bfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.88 6.103A21.35 21.35 0 0 0 24 2.5C12.126 2.5 2.5 12.126 2.5 24S12.126 45.5 24 45.5S45.5 35.874 45.5 24c0-4.397-1.335-8.475-3.602-11.879M45.5 2.5h-9.627l4.058 3.189l-1.979 1.979l2.381 2.38l1.978-1.979l3.189 4.058z");
}

</style>
