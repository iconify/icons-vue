<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8ve4cbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-timeline-outline-sharp" /></template>
<style>
.c8ve4cbty {
  fill: currentColor;
  d: path("M6 17h6v-2H6zm6-8h6V7h-6zm-3 4h6v-2H9zm-6 8V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
