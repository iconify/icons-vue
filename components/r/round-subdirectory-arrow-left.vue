<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx3hibg3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-subdirectory-arrow-left" /></template>
<style>
.xx3hibg3b {
  fill: currentColor;
  d: path("m5.71 15.71l4.58 4.58c.39.39 1.03.39 1.42 0s.39-1.03 0-1.42L8.83 16H19c.55 0 1-.45 1-1V5c0-.55-.45-1-1-1s-1 .45-1 1v9H8.83l2.88-2.87c.39-.39.39-1.03 0-1.42s-1.03-.39-1.42 0l-4.58 4.58c-.39.39-.39 1.03 0 1.42");
}

</style>
