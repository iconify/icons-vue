<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye60xpxiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thumbnail-bar-rounded" /></template>
<style>
.ye60xpxiv {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h4v16zm6 0V4h10q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20z");
}

</style>
