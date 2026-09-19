<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t2qp5xb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:topmixtapes" /></template>
<style>
.t2qp5xb4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.51 12.225v25.664m7.949-18.555v11.473M24.137 5.5v37M13.9 5.5h20.475m-18.556 9.113v20.805M7.541 19.361v11.282");
}

</style>
