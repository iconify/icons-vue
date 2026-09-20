<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vscu7rb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:redo-sharp" /></template>
<style>
.vscu7rb8y {
  fill: currentColor;
  d: path("M9.9 19q-2.425 0-4.163-1.575T4 13.5t1.738-3.925T9.9 8h6.3l-2.6-2.6L15 4l5 5l-5 5l-1.4-1.4l2.6-2.6H9.9q-1.575 0-2.738 1T6 13.5T7.163 16T9.9 17H17v2z");
}

</style>
