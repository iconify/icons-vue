<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s48z-1qmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ticket-horizontal-20-regular" /></template>
<style>
.s48z-1qmg {
  fill: currentColor;
  d: path("M16 5a2 2 0 0 1 2 2v.75c0 .428-.34.718-.687.762a1.5 1.5 0 0 0 0 2.976c.348.044.687.334.687.762V13a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-.75c0-.428.34-.718.688-.762a1.5 1.5 0 0 0 0-2.976C2.339 8.468 2 8.178 2 7.75V7a2 2 0 0 1 2-2zM4 6a1 1 0 0 0-1 1v.552a2.5 2.5 0 0 1 0 4.895V13a1 1 0 0 0 1 1h8v-1a.5.5 0 0 1 1 0v1h3a1 1 0 0 0 1-1v-.553a2.498 2.498 0 0 1 0-4.895V7a1 1 0 0 0-1-1h-3v1a.5.5 0 0 1-1 0V6zm8.5 2.5a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0V9a.5.5 0 0 1 .5-.5");
}

</style>
