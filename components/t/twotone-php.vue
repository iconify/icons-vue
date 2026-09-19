<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv5c3dbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-php" /></template>
<style>
.tv5c3dbza {
  fill: currentColor;
  d: path("M13 9h1.5v6H13v-2.5h-2V15H9.5V9H11v2h2zm-5 1.5v1c0 .8-.7 1.5-1.5 1.5h-2v2H3V9h3.5c.8 0 1.5.7 1.5 1.5m-1.5 0h-2v1h2zm15 0v1c0 .8-.7 1.5-1.5 1.5h-2v2h-1.5V9H20c.8 0 1.5.7 1.5 1.5m-1.5 0h-2v1h2z");
}

</style>
