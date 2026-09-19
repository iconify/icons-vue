<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zr5afzb9f"/><circle class="cpk0fnbgt"/><path class="mp1s3-l0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microchip" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mp1s3-l0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.97 13.26V2.59m-3.94 10.67V2.59m-3.94 10.67V3.32m11.82 9.94V3.32m-7.88 31.51V45.5m3.94-10.67V45.5m3.94-10.67v9.94m-11.82-9.94v9.94m16.69-18.75h10.67m-10.67-3.94h10.67m-10.67-3.94h9.94m-9.94 11.81h9.94m-31.5-7.87H2.55m10.67 3.94H2.55m10.67 3.93H3.28m9.94-11.81H3.28");
}

.zr5afzb9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.91 17.14h12.18a.76.76 0 0 1 .77.77v12.18a.76.76 0 0 1-.77.77H17.91a.76.76 0 0 1-.77-.77V17.91a.76.76 0 0 1 .77-.77");
}

</style>
