<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyo-2_bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timer-10-select-outline-sharp" /></template>
<style>
.qyo-2_bgb {
  fill: currentColor;
  d: path("M10 16h3V8h-3zm-3 3V5h9v14zm-4 0V8H1V5h5v14zm14 0v-2h4v-1h-4v-5h6v2h-4v1h4v5z");
}

</style>
