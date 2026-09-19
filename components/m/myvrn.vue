<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eys4akgsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myvrn" /></template>
<style>
.eys4akgsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.903 24l4.798-8.636h9.595L15.498 24l4.798 8.636h-9.595Zm21.801 18.5h9.595l4.798-8.636l-4.798-8.636l-4.797 8.636h-9.596Zm4.798-28.364l4.797 8.636l4.798-8.636L37.299 5.5h-9.595l-4.798 8.636Z");
}

</style>
