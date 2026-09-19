<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqhb9jy5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-details" /></template>
<style>
.qqhb9jy5i {
  fill: currentColor;
  d: path("m11.13 4.57l-8.3 14.94c-.37.67.11 1.49.87 1.49h16.6c.76 0 1.24-.82.87-1.49l-8.3-14.94a.997.997 0 0 0-1.74 0M13 8.92L18.6 19H13zm-2 0V19H5.4z");
}

</style>
