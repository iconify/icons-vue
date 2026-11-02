<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evubeznvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:minus-bulk-round" /></template>
<style>
.evubeznvy {
  fill: currentColor;
  d: path("M6 11h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

</style>
