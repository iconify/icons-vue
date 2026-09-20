<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tdo_nrbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-clock-20-regular" /></template>
<style>
.tdo_nrbhg {
  fill: currentColor;
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h9A2.5 2.5 0 0 1 17 5.5v9a2.5 2.5 0 0 1-2.5 2.5h-4.1q.244-.476.393-1H14.5a1.5 1.5 0 0 0 1.5-1.5V7H9.5A1.5 1.5 0 0 1 8 5.5V4H5.5A1.5 1.5 0 0 0 4 5.5v3.707q-.524.149-1 .393zM16 6v-.5A1.5 1.5 0 0 0 14.5 4H9v1.5a.5.5 0 0 0 .5.5zm-6 8.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0M5.5 12a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5H7a.5.5 0 0 0 0-1H6v-1.5a.5.5 0 0 0-.5-.5");
}

</style>
