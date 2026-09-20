<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dig2edbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thermostat-carbon-outline-sharp" /></template>
<style>
.dig2edbkl {
  fill: currentColor;
  d: path("M12 22.8L1.2 12L12 1.2L22.8 12zm0-2.8l8-8l-8-8l-8 8zm0-8");
}

</style>
