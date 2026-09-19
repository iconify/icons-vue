<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4qcmzb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-calendar-view-week" /></template>
<style>
.d4qcmzb-b {
  fill: currentColor;
  d: path("M22 4H2v16h20zm-9 2h2.5v12H13zm-2 12H8.5V6H11zM4 6h2.5v12H4zm16 12h-2.5V6H20z");
}

</style>
