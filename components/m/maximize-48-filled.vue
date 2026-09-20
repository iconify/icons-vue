<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ojy75ih5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:maximize-48-filled" /></template>
<style>
.ojy75ih5w {
  fill: currentColor;
  d: path("M6 11.5A5.5 5.5 0 0 1 11.5 6h25a5.5 5.5 0 0 1 5.5 5.5v25a5.5 5.5 0 0 1-5.5 5.5h-25A5.5 5.5 0 0 1 6 36.5zM11.5 9A2.5 2.5 0 0 0 9 11.5v25a2.5 2.5 0 0 0 2.5 2.5h25a2.5 2.5 0 0 0 2.5-2.5v-25A2.5 2.5 0 0 0 36.5 9z");
}

</style>
