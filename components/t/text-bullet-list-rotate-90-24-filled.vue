<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9amh-b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-rotate-90-24-filled" /></template>
<style>
.v9amh-b1p {
  fill: currentColor;
  d: path("M7.499 3.5a1.5 1.5 0 1 1-2.999 0a1.5 1.5 0 0 1 2.999 0m-.5 4v13.503a1 1 0 0 1-1.993.117L5 21.003V7.5a1 1 0 0 1 1.994-.116zm6.5-4a1.5 1.5 0 1 1-2.999 0a1.5 1.5 0 0 1 2.999 0m-.5 4v13.503a1 1 0 0 1-1.993.117L11 21.003V7.5a1 1 0 0 1 1.994-.116zm6.493-4a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m-.493 4v13.503a1 1 0 0 1-1.994.117L17 21.003V7.5a1 1 0 0 1 1.993-.116z");
}

</style>
