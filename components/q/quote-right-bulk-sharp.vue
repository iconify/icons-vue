<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa1k_bcwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:quote-right-bulk-sharp" /></template>
<style>
.xa1k_bcwd {
  fill: currentColor;
  d: path("M9 12V8H5v4Zm2 1c0 1.33-.522 2.597-1.464 3.536A5 5 0 0 1 6 18a1 1 0 0 1 0-2c1.27 0 2.405-.804 2.83-2H4a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1Zm8-1V8h-4v4Zm2 1c0 1.33-.522 2.597-1.464 3.536A5 5 0 0 1 16 18a1 1 0 0 1 0-2c1.27 0 2.405-.804 2.83-2H14a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1Z");
}

</style>
