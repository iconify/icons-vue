<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qyuvxcc7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:textbox-48-filled" /></template>
<style>
.qyuvxcc7p {
  fill: currentColor;
  d: path("M6 12a6 6 0 0 1 6-6h24a6 6 0 0 1 6 6v24a6 6 0 0 1-6 6H12a6 6 0 0 1-6-6zm9.25 10.5a1.25 1.25 0 1 0 0 2.5h10.5a1.25 1.25 0 1 0 0-2.5zM14 31.75c0 .69.56 1.25 1.25 1.25h17.5a1.25 1.25 0 1 0 0-2.5h-17.5c-.69 0-1.25.56-1.25 1.25m1.25-17.25a1.25 1.25 0 1 0 0 2.5h17.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
