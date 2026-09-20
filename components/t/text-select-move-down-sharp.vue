<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw-unsbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-select-move-down-sharp" /></template>
<style>
.uw-unsbig {
  fill: currentColor;
  d: path("M3 5V3h18v2zm9 12l-4-4l1.4-1.4l1.6 1.575V7h2v6.175l1.6-1.575L16 13zm-9 4v-2h18v2z");
}

</style>
