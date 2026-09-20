<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zshrdix0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-multiple-16-filled" /></template>
<style>
.zshrdix0l {
  fill: currentColor;
  d: path("M12.998 3.503c.606.456 1 1.18 1 1.997v5a4.5 4.5 0 0 1-4.5 4.5h-2a2.5 2.5 0 0 1-2.123-1.185c.353.119.73.185 1.123.185h3a3.5 3.5 0 0 0 3.5-3.5zM9.5 1A2.5 2.5 0 0 1 12 3.5v7A2.5 2.5 0 0 1 9.5 13h-4A2.5 2.5 0 0 1 3 10.5v-7A2.5 2.5 0 0 1 5.5 1zM7.147 5.111A.75.75 0 0 0 6 5.747v2.498a.75.75 0 0 0 1.147.636l1.998-1.25a.75.75 0 0 0 0-1.27z");
}

</style>
