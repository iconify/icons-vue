<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h--f36j1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-signal-wifi-statusbar-4-bar" /></template>
<style>
.h--f36j1w {
  fill: currentColor;
  d: path("M12 4C7.7 4 3.78 5.6.79 8.24C.35 8.63.32 9.3.73 9.71l10.56 10.58c.39.39 1.02.39 1.42 0L23.27 9.71c.41-.41.38-1.08-.06-1.47A16.87 16.87 0 0 0 12 4");
}

</style>
