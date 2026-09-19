<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mjk7labqf"/><circle class="tzr8h2b3t"/><circle class="jmbr51bop"/><path class="afnu92b3a"/><circle class="xfhhefs5g"/><path class="cgw-qsgpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:panasonic-tv-share" /></template>
<style>
.afnu92b3a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.973 29.032c1.948 1.935 2.638 4.918 1.795 7.76m-9.899-8.998c1.638-.78 3.443-.957 5.106-.5");
}

.cgw-qsgpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.244 36.79v2.066m-5.614 0h10.134");
}

.jmbr51bop {
  cx: 25.785px;
  cy: 28.245px;
  r: 3.781px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mjk7labqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.97 18.376l-24.09-3.47V36.79h33.07V23.34");
}

.tzr8h2b3t {
  cx: 35.913px;
  cy: 16.363px;
  r: 7.218px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xfhhefs5g {
  cx: 12.38px;
  cy: 26.593px;
  r: 2.521px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
