<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vndq6ubqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-turn-slight-right" /></template>
<style>
.vndq6ubqz {
  fill: currentColor;
  d: path("M12.34 5c0-.55.45-1 1-1H17c.55 0 1 .45 1 1v3.66c0 .55-.45 1-1 1s-1-.45-1-1V7.41l-5 5V19c0 .55-.45 1-1 1s-1-.45-1-1v-6.58c0-.53.21-1.04.59-1.41l5-5h-1.24A1.02 1.02 0 0 1 12.34 5");
}

</style>
