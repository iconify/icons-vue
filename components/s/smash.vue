<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hfxpj4baq"/><path class="mlgoyvtjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smash" /></template>
<style>
.hfxpj4baq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.955 6.7C5.92-1.301-2.006 39.293 13.817 34.03l19.304-7.132");
}

.mlgoyvtjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.948 21.068l18.448-6.412c17-6.038 8.89 34.539-17.557 26.676");
}

</style>
