<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xkso94oal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:stack-vertical-20-filled" /></template>
<style>
.xkso94oal {
  fill: currentColor;
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h9A2.5 2.5 0 0 1 17 5.5v10.75a.75.75 0 0 1-1.5 0V13.5a1 1 0 0 0-1-1h-9a1 1 0 0 0-1 1v2.75a.75.75 0 0 1-1.5 0zm1.5 5.708a2.5 2.5 0 0 1 1-.208h9c.356 0 .694.074 1 .208V9.5a1 1 0 0 0-1-1h-9a1 1 0 0 0-1 1zm11-5.708a1 1 0 0 0-1-1h-9a1 1 0 0 0-1 1v1.708A2.5 2.5 0 0 1 5.5 7h9c.356 0 .694.074 1 .208z");
}

</style>
