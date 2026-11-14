<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8468c6yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-visual-24-filled" /></template>
<style>
.d8468c6yn {
  fill: currentColor;
  d: path("M4 14a1 1 0 0 1 1 1v2.5A1.5 1.5 0 0 0 6.5 19H9a1 1 0 1 1 0 2H6.5A3.5 3.5 0 0 1 3 17.5V15a1 1 0 0 1 1-1m16 0a1 1 0 0 1 1 1v2.5a3.5 3.5 0 0 1-3.5 3.5H15a1 1 0 1 1 0-2h2.5a1.5 1.5 0 0 0 1.5-1.5V15a1 1 0 0 1 1-1m-8-5.5a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7m0 2a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3M9 3a1 1 0 0 1 0 2H6.5A1.5 1.5 0 0 0 5 6.5V9a1 1 0 1 1-2 0V6.5A3.5 3.5 0 0 1 6.5 3zm8.5 0A3.5 3.5 0 0 1 21 6.5V9a1 1 0 1 1-2 0V6.5A1.5 1.5 0 0 0 17.5 5H15a1 1 0 1 1 0-2zm-10 3.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
