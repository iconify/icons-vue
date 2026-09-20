<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="alqwtxb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-default-32-regular" /></template>
<style>
.alqwtxb-h {
  fill: currentColor;
  d: path("M3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5zM7.5 5A2.5 2.5 0 0 0 5 7.5V11h6V5zM5 13v6h6v-6zm8 0v6h6v-6zm8 0v6h6v-6zm-2 8h-6v6h6zm2 6h3.5a2.5 2.5 0 0 0 2.5-2.5V21h-6zm0-16h6V7.5A2.5 2.5 0 0 0 24.5 5H21zm-2-6h-6v6h6zM5 21v3.5A2.5 2.5 0 0 0 7.5 27H11v-6z");
}

</style>
