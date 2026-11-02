<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaw40v7pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ticket-fill" /></template>
<style>
.yaw40v7pb {
  fill: currentColor;
  d: path("M13 19H5a3 3 0 0 1-3-3v-1a1 1 0 0 1 1-1a2 2 0 1 0 0-4a1 1 0 0 1-1-1V8a3 3 0 0 1 3-3h8Zm2 0V5h4a3 3 0 0 1 3 3v1a1 1 0 0 1-1 1a2 2 0 1 0 0 4a1 1 0 0 1 1 1v1a3 3 0 0 1-3 3Z");
}

</style>
