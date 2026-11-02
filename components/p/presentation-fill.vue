<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pryzwm8nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:presentation-fill" /></template>
<style>
.pryzwm8nd {
  fill: currentColor;
  d: path("M3 2h18a1 1 0 0 1 0 2h-1v10a3 3 0 0 1-3 3h-2.586l3.293 3.293a.999.999 0 1 1-1.414 1.414L12 17.414l-4.293 4.293a.999.999 0 1 1-1.414-1.414L9.586 17H7a3 3 0 0 1-3-3V4H3a1 1 0 0 1 0-2m6.728 15h.654a1 1 0 0 0-.654 0m3.89 0h.654a1 1 0 0 0-.654 0");
}

</style>
