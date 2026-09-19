<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9-_98h5r"/><path class="ih6i9g6vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-pin-drop" /></template>
<style>
.e9-_98h5r {
  fill: currentColor;
  d: path("M12 4c1.93 0 5 1.4 5 5.15c0 2.16-1.72 4.67-5 7.32c-3.28-2.65-5-5.17-5-7.32C7 5.4 10.07 4 12 4m0-2C8.73 2 5 4.46 5 9.15c0 3.12 2.33 6.41 7 9.85c4.67-3.44 7-6.73 7-9.85C19 4.46 15.27 2 12 2");
}

.ih6i9g6vx {
  fill: currentColor;
  d: path("M12 7c-1.1 0-2 .9-2 2s.9 2 2 2a2 2 0 1 0 0-4M5 20h14v2H5z");
}

</style>
