<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk3pjcbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-cursor-bulk-round" /></template>
<style>
.xk3pjcbbh {
  fill: currentColor;
  d: path("M12 3.998a5.04 5.04 0 0 1 2.053-1.605A5 5 0 0 1 16 2a1 1 0 0 1 0 2a3 3 0 0 0-3 3v10a3 3 0 0 0 3 3a1 1 0 0 1 0 2a5 5 0 0 1-1.947-.393A5.04 5.04 0 0 1 12 20.002a5.04 5.04 0 0 1-2.053 1.605A5 5 0 0 1 8 22a1 1 0 0 1 0-2a3 3 0 0 0 3-3V7a3 3 0 0 0-3-3a1 1 0 0 1 0-2a5 5 0 0 1 1.947.393A5.04 5.04 0 0 1 12 3.998");
}

</style>
