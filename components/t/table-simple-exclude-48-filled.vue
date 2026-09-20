<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f6myxeyln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-exclude-48-filled" /></template>
<style>
.f6myxeyln {
  fill: currentColor;
  d: path("M10.25 4A6.25 6.25 0 0 0 4 10.25v8.25h14.5V4zM4 29.25V21h14.5v14.5h-8.25A6.25 6.25 0 0 1 4 29.25m31.5-19v8.25H21V4h8.25a6.25 6.25 0 0 1 6.25 6.25m-10.5 19A4.25 4.25 0 0 1 29.25 25h10.5A4.25 4.25 0 0 1 44 29.25v10.5A4.25 4.25 0 0 1 39.75 44h-10.5A4.25 4.25 0 0 1 25 39.75z");
}

</style>
