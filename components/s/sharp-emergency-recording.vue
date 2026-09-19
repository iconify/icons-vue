<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t386oohwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-emergency-recording" /></template>
<style>
.t386oohwx {
  fill: currentColor;
  d: path("M18 10.48V4H2v16h16v-6.48l4 3.98v-11zM12 12l3 1.73l-1 1.73l-3-1.73V17H9v-3.27l-3 1.73l-1-1.73L8 12l-3-1.73l1-1.73l3 1.73V7h2v3.27l3-1.73l1 1.73z");
}

</style>
