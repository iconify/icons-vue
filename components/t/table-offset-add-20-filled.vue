<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xf8hmqj4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-offset-add-20-filled" /></template>
<style>
.xf8hmqj4o {
  fill: currentColor;
  d: path("M5.5 3H12v4H3V5.5A2.5 2.5 0 0 1 5.5 3M8 8h9v1.6A5.5 5.5 0 0 0 9.6 12H8zm1 6.5a5.5 5.5 0 0 1 .207-1.5H3v1.5A2.5 2.5 0 0 0 5.5 17h4.1a5.5 5.5 0 0 1-.6-2.5M7 12V8H3v4zm6-5h4V5.5A2.5 2.5 0 0 0 14.5 3H13zm6 7.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15z");
}

</style>
