<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bto6i3bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-48-regular" /></template>
<style>
.bto6i3bgr {
  fill: currentColor;
  d: path("M18.545 7.202c2.385-4.27 8.528-4.27 10.913 0l14.242 25.5C46.026 36.868 43.014 42 38.243 42H9.76c-4.772 0-7.783-5.132-5.456-9.298zm8.73 1.219c-1.43-2.562-5.116-2.561-6.547 0L6.485 33.92c-1.396 2.5.41 5.579 3.274 5.579h28.484c2.863 0 4.67-3.08 3.275-5.58zM24 30a2 2 0 1 1 0 4a2 2 0 0 1 0-4m0-15c.69 0 1.25.56 1.25 1.25v9.5a1.25 1.25 0 0 1-2.5 0v-9.5c0-.69.56-1.25 1.25-1.25");
}

</style>
