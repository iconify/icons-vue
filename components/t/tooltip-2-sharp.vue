<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s49ndol6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tooltip-2-sharp" /></template>
<style>
.s49ndol6m {
  fill: currentColor;
  d: path("M6.5 13.75h7v-1h-7zm0-3h11v-1h-11zm0-3h11v-1h-11zM12 21l-2.29-3.5H3V3h18v14.5h-6.71z");
}

</style>
