<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m0n9q152t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-neoma-bs" /></template>
<style>
.m0n9q152t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.856 7.49c7.39 7.831 8.247 22.796.03 33.049c19.591-3.406 19.39-28.317-.03-33.048m-9.891-.03C-.34 12.864-.34 35.748 19.084 40.421c-7.901-9.835-8.24-22.91-.119-32.96");
}

</style>
