<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w0r4ifbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ostgotatrafiken" /></template>
<style>
.w0r4ifbie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.8 13.847a13.252 13.252 0 1 1-8.518-3.1m0 0H43.5m-28.267 0H4.5");
}

</style>
