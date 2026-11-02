<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs4oiabyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-sparkle-fill" /></template>
<style>
.qs4oiabyq {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h2a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0Zm17-3a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-2a1 1 0 0 1 0-2Zm-8 5a1 1 0 0 1 2 0c0 1.07.311 2.146 1.082 2.918c.348.348.771.613 1.23.789A4.7 4.7 0 0 0 17 11a1 1 0 0 1 0 2c-.574 0-1.151.086-1.688.293a3.5 3.5 0 0 0-1.23.789a3.5 3.5 0 0 0-.789 1.23A4.7 4.7 0 0 0 13 17a1 1 0 0 1-2 0c0-.574-.086-1.151-.293-1.688a3.5 3.5 0 0 0-.789-1.23C9.146 13.311 8.07 13 7 13a1 1 0 0 1 0-2c2.444 0 4-1.556 4-4M2 19v-2a1 1 0 0 1 2 0v2a1 1 0 0 0 1 1h2a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3m17 3h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0v2a3 3 0 0 1-3 3");
}

</style>
