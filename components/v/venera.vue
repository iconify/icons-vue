<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ccnoxxb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:venera" /></template>
<style>
.ccnoxxb5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 7.872L25.897 40.128M5.5 7.872l16.603 32.256M12.036 7.872L24 31.116L35.964 7.872");
}

</style>
