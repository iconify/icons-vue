<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vi7cghb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:minimize-48-filled" /></template>
<style>
.vi7cghb8h {
  fill: currentColor;
  d: path("M6 23.5A1.5 1.5 0 0 1 7.5 22h33a1.5 1.5 0 0 1 0 3h-33A1.5 1.5 0 0 1 6 23.5");
}

</style>
