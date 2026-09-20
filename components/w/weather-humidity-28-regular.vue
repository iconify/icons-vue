<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="a-_5gobil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-humidity-28-regular" /></template>
<style>
.a-_5gobil {
  fill: currentColor;
  d: path("M17.25 24.5a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1 0-1.5zm3-3a.75.75 0 0 1 0 1.5H7.75a.75.75 0 0 1 0-1.5zm1.25-3a.75.75 0 0 1 0 1.5h-15a.75.75 0 0 1 0-1.5zm.25-3a.75.75 0 0 1 0 1.5H6.25a.75.75 0 0 1 0-1.5zM13.47 2.22a.75.75 0 0 1 1.06 0c.523.523 2.494 2.614 4.34 5.315c1.298 1.9 2.584 4.18 3.22 6.465h-1.563c-.597-1.896-1.694-3.858-2.896-5.618A41 41 0 0 0 14 3.836a41 41 0 0 0-3.63 4.546c-1.204 1.76-2.3 3.722-2.897 5.618H5.91c.635-2.285 1.922-4.564 3.22-6.465c1.846-2.701 3.817-4.792 4.34-5.315");
}

</style>
