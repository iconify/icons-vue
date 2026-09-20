<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xe3n-bb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:maximize-48-regular" /></template>
<style>
.xe3n-bb3j {
  fill: currentColor;
  d: path("M6 11.25C6 8.35 8.35 6 11.25 6h25.5C39.65 6 42 8.35 42 11.25v25.5c0 2.9-2.35 5.25-5.25 5.25h-25.5A5.25 5.25 0 0 1 6 36.75zm5.25-2.75a2.75 2.75 0 0 0-2.75 2.75v25.5a2.75 2.75 0 0 0 2.75 2.75h25.5a2.75 2.75 0 0 0 2.75-2.75v-25.5a2.75 2.75 0 0 0-2.75-2.75z");
}

</style>
