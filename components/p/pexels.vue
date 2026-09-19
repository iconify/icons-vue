<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nzszlsp8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pexels" /></template>
<style>
.nzszlsp8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.048 4.5H9.568v39h10.006V33.269h4.474c7.944 0 14.385-6.44 14.385-14.385S31.993 4.5 24.048 4.5");
}

</style>
