<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="yi3jqyb4m"/><path class="z_rc4vb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:material-flashlight" /></template>
<style>
.yi3jqyb4m {
  cx: 19.033px;
  cy: 29.294px;
  r: 3.506px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z_rc4vb0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.033 9.427l18.699 18.698M19.033 20.18L6.178 33.034L15.41 42.5l12.856-14.024l9.7-.304l3.856-3.973L23.123 5.5l-4.207 4.09Z");
}

</style>
