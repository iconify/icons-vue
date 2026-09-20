<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eaj6b6-8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-lock-32-regular" /></template>
<style>
.eaj6b6-8z {
  fill: currentColor;
  d: path("M23 16.5a3.5 3.5 0 0 1 3.5 3.5v.5h.5a2.5 2.5 0 0 1 2.5 2.5v6a2.5 2.5 0 0 1-2.5 2.5h-8a2.5 2.5 0 0 1-2.5-2.5v-6a2.5 2.5 0 0 1 2.5-2.5h.5V20a3.5 3.5 0 0 1 3.5-3.5m0 7.5a2 2 0 1 0 0 4a2 2 0 0 0 0-4m-7-7c.956 0 1.806.45 2.355 1.146a5 5 0 0 0-.275.96c-.419.1-.812.265-1.169.484A1 1 0 0 0 16 19H5a1 1 0 0 0-1 1v.19q0 .025.009.093c.01.09.03.232.076.406c.09.347.273.818.642 1.29C5.43 22.885 6.98 24 10.5 24c2.15 0 3.564-.419 4.5-.95v2.207c-1.16.456-2.634.743-4.5.743c-3.98 0-6.181-1.29-7.352-2.792a5.6 5.6 0 0 1-.999-2.018a5 5 0 0 1-.146-.897L2 20.227V20a3 3 0 0 1 3-3zm7 1.5a1.5 1.5 0 0 0-1.5 1.5v.5h3V20a1.5 1.5 0 0 0-1.5-1.5M10.5 4a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M23 7a4 4 0 1 1 0 8a4 4 0 0 1 0-8M10.5 6a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7M23 9a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>
