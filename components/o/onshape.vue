<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kjq4ubbvc"/><path class="yw26d6ulm"/><path class="cxqzoqmjd"/><path class="y8lbv3_fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:onshape" /></template>
<style>
.cxqzoqmjd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.67 21.5v5L24 29l4.33-2.5v-5L24 19z");
}

.kjq4ubbvc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.175 17.75v12.5L24 36.5l10.825-6.25v-12.5L24 11.5z");
}

.y8lbv3_fl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.639 19.75v8.5L24 32.5l7.361-4.25v-8.5L24 15.5zm18.186 10.5v8M28.33 26.5V30M24 11.5l6.928-4M13.175 30.25l-6.928-4m20.784-9L24 19m-7.361 5.75l3.031 1.75");
}

.yw26d6ulm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.247 13.75v20.5L24 44.5l17.754-10.25v-20.5L24 3.5z");
}

</style>
