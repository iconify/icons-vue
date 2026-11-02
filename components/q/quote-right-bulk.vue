<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctxwunbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:quote-right-bulk" /></template>
<style>
.ctxwunbdb {
  fill: currentColor;
  d: path("M9 12V9a.997.997 0 0 0-1-1H6a1 1 0 0 0-1 1v2a.997.997 0 0 0 1 1Zm2 1c0 1.33-.522 2.597-1.464 3.536A5 5 0 0 1 6 18a1 1 0 0 1 0-2c1.27 0 2.405-.804 2.83-2H6a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3Zm8-1V9a1 1 0 0 0-1-1h-2a.997.997 0 0 0-1 1v2a.997.997 0 0 0 1 1Zm2 1c0 1.33-.522 2.597-1.464 3.536A5 5 0 0 1 16 18a1 1 0 0 1 0-2c1.27 0 2.405-.804 2.83-2H16a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3Z");
}

</style>
