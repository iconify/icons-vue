<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xaaymjtie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monitor-outline-sharp" /></template>
<style>
.xaaymjtie {
  fill: currentColor;
  d: path("M7.192 20v-1.538l.77-.77H3V4h18v13.692h-4.962l.77.77V20zM4 16.692h16V5H4zm0 0V5z");
}

</style>
