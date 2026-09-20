<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="zrkquobtk"/><path class="dfyqqgb3q"/><circle class="a8pel9khv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sidcheck" /></template>
<style>
.a8pel9khv {
  cx: 23.989px;
  cy: 21.175px;
  r: 2.471px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dfyqqgb3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.553 15.994A10.447 10.447 0 0 1 24 5.547a10.447 10.447 0 0 1 10.447 10.447m-16.025 9.903h11.156a2.775 2.775 0 0 1 2.775 2.775v8.903a2.775 2.775 0 0 1-2.775 2.775H18.422a2.775 2.775 0 0 1-2.775-2.775v-8.903a2.775 2.775 0 0 1 2.775-2.775m1.121 4.818h12.81m-16.706 4.817h12.81");
}

.zrkquobtk {
  width: 28.73px;
  height: 26.118px;
  x: 9.635px;
  y: 16.468px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
}

</style>
