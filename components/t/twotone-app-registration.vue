<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s79a-jboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-app-registration" /></template>
<style>
.s79a-jboz {
  fill: currentColor;
  d: path("M10 4h4v4h-4zM4 16h4v4H4zm0-6h4v4H4zm0-6h4v4H4zm12 0h4v4h-4zm-5 13.86V20h2.1l5.98-5.97l-2.12-2.12zm3-5.83V10h-4v4h2.03zm6.85-.47l-1.41-1.41c-.2-.2-.51-.2-.71 0l-1.06 1.06l2.12 2.12l1.06-1.06c.2-.2.2-.51 0-.71");
}

</style>
