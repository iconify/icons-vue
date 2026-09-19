<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bg6-97biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pr0gramm" /></template>
<style>
.bg6-97biw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.12 7l17 17l-17 17l-4.62-4.67L17.83 24L5.5 11.67ZM24 41h18.5v-6.21H24Z");
}

</style>
