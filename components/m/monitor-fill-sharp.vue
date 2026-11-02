<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruc7hnxun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-fill-sharp" /></template>
<style>
.ruc7hnxun {
  fill: currentColor;
  d: path("M3 17V4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m12 2a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

</style>
