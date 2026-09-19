<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jvs88gdky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:revolution" /></template>
<style>
.jvs88gdky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.1 6.33a2.56 2.56 0 0 0-2.57 2.56v7.66h-9L8.8 24v15.1a2.56 2.56 0 0 0 2.56 2.58h20.09A2.58 2.58 0 0 0 34 39.11v-7.66h2.6a2.55 2.55 0 0 0 2.57-2.56h0V13.77l4.3-7.44zM34 31.45V19.12a2.57 2.57 0 0 0-2.56-2.57H13.53m5.39 5.02v15.08m5.02-15.08v15.08m5.03-10.05H13.89m15.08 5.02H13.89");
}

</style>
