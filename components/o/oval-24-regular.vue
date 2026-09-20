<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjyfqsbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:oval-24-regular" /></template>
<style>
.mjyfqsbbl {
  fill: currentColor;
  d: path("M2 12a8 8 0 0 1 8-8h4a8 8 0 1 1 0 16h-4a8 8 0 0 1-8-8m8-6.5a6.5 6.5 0 0 0 0 13h4a6.5 6.5 0 1 0 0-13z");
}

</style>
