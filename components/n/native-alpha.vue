<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qi8881brs"/><path class="pkynabcrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:native-alpha" /></template>
<style>
.pkynabcrj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.74 29.5v-11l8 11v-11");
}

.qi8881brs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 9.335a5.5 5.5 0 0 0-3.921 0c-12.23 5.333-9.17 29.594-22.509 29.33C10.633 38.535 4.504 33.097 4.5 24S10.633 9.463 17.07 9.335c13.34-.265 10.279 23.997 22.508 29.33a5.5 5.5 0 0 0 3.922 0");
}

</style>
