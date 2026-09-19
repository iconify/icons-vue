<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n0577s69b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:signal-detector" /></template>
<style>
.n0577s69b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 26.585h5.207l2.652-4.146l4.504 10.752l4.709-18.382l6.093 15.825l5.96-10.882l4.744 6.802H43.5");
}

</style>
