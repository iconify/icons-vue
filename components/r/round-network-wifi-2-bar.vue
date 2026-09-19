<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwr7enbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-network-wifi-2-bar" /></template>
<style>
.qwr7enbld {
  fill: currentColor;
  d: path("M12 4C7.7 4 3.78 5.6.79 8.24C.35 8.63.32 9.3.73 9.71l10.56 10.58c.39.39 1.02.39 1.42 0L23.27 9.71c.41-.41.38-1.08-.06-1.47A16.87 16.87 0 0 0 12 4m4.78 9.38A8.85 8.85 0 0 0 12 12c-1.76 0-3.4.5-4.78 1.38l-4.3-4.3C5.51 7.08 8.67 6 12 6s6.49 1.08 9.08 3.07z");
}

</style>
