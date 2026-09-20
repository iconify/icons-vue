<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vhcpikybp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-exclude-20-filled" /></template>
<style>
.vhcpikybp {
  fill: currentColor;
  d: path("M4.5 2H8v6H2V4.5A2.5 2.5 0 0 1 4.5 2M2 9v3.5A2.5 2.5 0 0 0 4.5 15H8V9zm13-1V4.5A2.5 2.5 0 0 0 12.5 2H9v6zm-4 5a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2z");
}

</style>
