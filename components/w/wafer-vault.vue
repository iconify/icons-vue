<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="danhkfbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wafer-vault" /></template>
<style>
.danhkfbya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.198 35.118A17.72 17.72 0 0 0 40.108 24c0-9.833-7.97-17.804-17.804-17.804S4.5 14.166 4.5 24s7.971 17.804 17.804 17.804H43.5zm-13.841-2.616V15.498m7.363 12.753l-14.725-8.502m0 8.502l14.725-8.502");
}

</style>
