<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9-d2xaot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:quote-single-right-bulk-sharp" /></template>
<style>
.r9-d2xaot {
  fill: currentColor;
  d: path("M14 12V8h-4v4Zm2 1c0 1.33-.522 2.597-1.464 3.536A5 5 0 0 1 11 18a1 1 0 0 1 0-2c1.27 0 2.405-.804 2.83-2H9a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1Z");
}

</style>
