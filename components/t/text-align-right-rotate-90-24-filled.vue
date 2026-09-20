<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otkohtedb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-right-rotate-90-24-filled" /></template>
<style>
.otkohtedb {
  fill: currentColor;
  d: path("M18 5a1 1 0 0 1 1 1v15a1 1 0 1 1-2 0V6a1 1 0 0 1 1-1M6 9a1 1 0 0 1 1 1v11a1 1 0 1 1-2 0V10a1 1 0 0 1 1-1m7-6a1 1 0 1 0-2 0v18a1 1 0 1 0 2 0z");
}

</style>
