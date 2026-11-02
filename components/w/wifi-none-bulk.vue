<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmnzmsbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-none-bulk" /></template>
<style>
.fmnzmsbfw {
  fill: currentColor;
  d: path("M12 18h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
