<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="obxduubug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mensinator" /></template>
<style>
.obxduubug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5C14.242 13.834 8.68 19.71 8.676 28.168v.008C8.676 36.64 15.536 43.5 24 43.5q.793 0 1.566-.08c7.727-.784 13.758-7.31 13.758-15.244v-.01C39.319 19.708 33.758 13.834 24 4.5M17.785 24h12.43m-12.43 10.145h12.43M24 30.215v-12.43");
}

</style>
