<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olzswx62l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mailbox-fill-round" /></template>
<style>
.olzswx62l {
  fill: currentColor;
  d: path("M8 8h8V3a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2h-3v4.099A5.01 5.01 0 0 1 22 13v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22h-5v-9a5.01 5.01 0 0 0-4-4.901Zm2 5v9H7a5 5 0 0 1-5-5v-4a5.01 5.01 0 0 1 4-4.901V9a1 1 0 0 0 1 1a3 3 0 0 1 3 3");
}

</style>
