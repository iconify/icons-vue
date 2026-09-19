<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p5eravn5u"/><path class="gq9lqwxth"/><path class="osoj51v-y"/><path class="h_xkm6cxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pocket-city" /></template>
<style>
.gq9lqwxth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.422 38.495l.011-9.169l20.86-.01v9.361");
}

.h_xkm6cxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.545 21.5h3.283v3.284h-3.283zm5.596 0h3.283v3.284h-3.283zm0-5.257h3.283v3.283h-3.283zm-5.596 0h3.283v3.283h-3.283zm-3.53 17.482H28.3v3.283h-3.283zm-5.596 0h3.283v3.283H19.42zM15.9 22.716h3.283V26H15.9zm-5.597 0h3.283V26h-3.283z");
}

.osoj51v-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.364 29.322v-17.1h15.732m-32.83 7.242h17.098");
}

.p5eravn5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.907 44.5L6.226 34.374l.055-20.7L23.907 3.5l17.811 10.229l.055 20.756z");
}

</style>
