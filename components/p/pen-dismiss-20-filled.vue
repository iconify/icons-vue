<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m7p0z2biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pen-dismiss-20-filled" /></template>
<style>
.m7p0z2biz {
  fill: currentColor;
  d: path("M12.92 2.873a2.975 2.975 0 0 1 4.207 4.207L15 9.207A5.5 5.5 0 0 0 8.207 16l-.438.438a2.5 2.5 0 0 1-1.234.678l-3.926.873a.5.5 0 0 1-.597-.597l.878-3.95c.1-.452.328-.867.655-1.194zM18 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-2.646-1.146a.5.5 0 0 0-.708-.708L13.5 13.793l-1.146-1.147a.5.5 0 0 0-.708.708l1.147 1.146l-1.147 1.146a.5.5 0 0 0 .708.708l1.146-1.147l1.146 1.147a.5.5 0 0 0 .708-.708L14.207 14.5z");
}

</style>
