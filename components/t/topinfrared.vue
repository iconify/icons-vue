<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p_zbhkb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:topinfrared" /></template>
<style>
.p_zbhkb7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 15.268l8.65-8.91h14.319v35.283h-9.034V15.268zm22.969-.513H42.5V6.359H28.469");
}

</style>
