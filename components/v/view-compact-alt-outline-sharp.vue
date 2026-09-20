<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi3llcbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-compact-alt-outline-sharp" /></template>
<style>
.zi3llcbne {
  fill: currentColor;
  d: path("M8.25 15.75h3v-3h-3zm0-4.5h3v-3h-3zm4.5 4.5h3v-3h-3zm0-4.5h3v-3h-3zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
