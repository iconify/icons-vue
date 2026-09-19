<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zzyq9obwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:om" /></template>
<style>
.zzyq9obwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.68 26.53H7a2.53 2.53 0 0 1 0-5.06h12.68a2.53 2.53 0 0 1 0 5.06m21.29 0H28.32a2.53 2.53 0 0 1 0-5.06H41a2.53 2.53 0 0 1 0 5.06Z");
}

</style>
