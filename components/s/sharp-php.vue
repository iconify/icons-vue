<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uckdlxb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-php" /></template>
<style>
.uckdlxb-p {
  fill: currentColor;
  d: path("M13 9h1.5v6H13v-2.5h-2V15H9.5V9H11v2h2zM8 9v4H4.5v2H3V9zm-1.5 1.5h-2v1h2zm15-1.5v4H18v2h-1.5V9zM20 10.5h-2v1h2z");
}

</style>
