<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ixijtj9ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mcm-axess" /></template>
<style>
.ixijtj9ur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 6.546l19 32.908H5zm0 0v21.939m19 10.969L24 28.485M5 39.454l19-10.969");
}

</style>
