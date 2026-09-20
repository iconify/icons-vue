<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zu__41y8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-snowflake-48-filled" /></template>
<style>
.zu__41y8y {
  fill: currentColor;
  d: path("M24.5 4A1.5 1.5 0 0 1 26 5.5v7.827l4.503-4.503a1.5 1.5 0 0 1 2.122 2.121L26 17.57V23h5.43l6.625-6.625a1.5 1.5 0 0 1 2.121 2.122L35.673 23H43.5a1.5 1.5 0 0 1 0 3h-7.827l4.26 4.26a1.5 1.5 0 0 1-2.122 2.121L31.43 26H26v5.43l6.381 6.381a1.5 1.5 0 0 1-2.121 2.121L26 35.673V43.5a1.5 1.5 0 0 1-3 0v-7.827l-4.503 4.503a1.5 1.5 0 0 1-2.122-2.121L23 31.43V26h-5.43l-6.625 6.625a1.5 1.5 0 0 1-2.121-2.122L13.327 26H5.5a1.5 1.5 0 0 1 0-3h7.827L8.58 18.253a1.5 1.5 0 0 1 2.122-2.121L17.57 23H23v-5.43l-6.868-6.868a1.5 1.5 0 0 1 2.121-2.122L23 13.327V5.5A1.5 1.5 0 0 1 24.5 4");
}

</style>
