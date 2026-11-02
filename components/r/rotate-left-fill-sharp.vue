<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6iqykjnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-left-fill-sharp" /></template>
<style>
.i6iqykjnx {
  fill: currentColor;
  d: path("M15.707 3.707L14.414 5H19a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V7h-3.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414M20 14v6a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2H6v12h12v-5a1 1 0 0 1 2 0");
}

</style>
