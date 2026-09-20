<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5hr1fbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-outline-sharp" /></template>
<style>
.h5hr1fbfx {
  fill: currentColor;
  d: path("M8 21v-2H2V3h20v16h-6v2zm-4-4h16V5H4zm0 0V5z");
}

</style>
