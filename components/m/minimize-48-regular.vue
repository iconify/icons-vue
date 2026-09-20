<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q6jxdobki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:minimize-48-regular" /></template>
<style>
.q6jxdobki {
  fill: currentColor;
  d: path("M6 23.25c0-.69.56-1.25 1.25-1.25h33.5a1.25 1.25 0 1 1 0 2.5H7.25c-.69 0-1.25-.56-1.25-1.25");
}

</style>
