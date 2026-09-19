<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r_a32gbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tageditor" /></template>
<style>
.r_a32gbyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 10.905h-6.522v21.668m0 0a4.522 4.522 0 1 1-9.043 0a4.522 4.522 0 0 1 9.043 0M27.33 10.905H5.5m21.83 8.616H5.5m13.248 8.616H5.5");
}

</style>
