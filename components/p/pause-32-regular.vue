<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e_bzyj0wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pause-32-regular" /></template>
<style>
.e_bzyj0wx {
  fill: currentColor;
  d: path("M7.25 3A3.25 3.25 0 0 0 4 6.25v18.5A3.25 3.25 0 0 0 7.25 28h3.5A3.25 3.25 0 0 0 14 24.75V6.25A3.25 3.25 0 0 0 10.75 3zM6 6.25C6 5.56 6.56 5 7.25 5h3.5c.69 0 1.25.56 1.25 1.25v18.5c0 .69-.56 1.25-1.25 1.25h-3.5C6.56 26 6 25.44 6 24.75zM21.25 3A3.25 3.25 0 0 0 18 6.25v18.5A3.25 3.25 0 0 0 21.25 28h3.5A3.25 3.25 0 0 0 28 24.75V6.25A3.25 3.25 0 0 0 24.75 3zM20 6.25c0-.69.56-1.25 1.25-1.25h3.5c.69 0 1.25.56 1.25 1.25v18.5c0 .69-.56 1.25-1.25 1.25h-3.5c-.69 0-1.25-.56-1.25-1.25z");
}

</style>
