<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z8_a0ii5m"/><path class="tawl1fbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minecraft-sword" /></template>
<style>
.tawl1fbpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.187 5.5h-4.625v2.312H33.25v2.313h-2.313v2.312h-2.312v2.313h-2.313v2.312H24v2.313h-2.313v2.313h-2.312v4.624h2.312v2.313h4.625v-2.313h2.313V24h2.312v-2.312h2.313v-2.313h2.312v-2.313h2.313V14.75h2.312v-2.313H42.5V5.5zM14.75 30.937h-2.313v2.313h-2.312v2.312H5.5V42.5h6.937v-4.625h2.313v-2.313h2.312v-4.625z");
}

.z8_a0ii5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 28.625v2.312h2.312v2.313h2.313v2.312H24v2.313h4.625V33.25h-2.313v-2.313H24v-2.312h-2.313v-2.313h-2.312v-2.273h-2.313v-2.313H14.75v-2.273h-4.625v4.586h2.312v4.586z");
}

</style>
