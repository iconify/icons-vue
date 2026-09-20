<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr48w-lul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-select-end-outline" /></template>
<style>
.tr48w-lul {
  fill: currentColor;
  d: path("M11 5V3h2v2zm0 16v-2h2v2zM7 5V3h2v2zm0 16v-2h2v2zM3 5V3h2v2zm0 4V7h2v2zm0 4v-2h2v2zm0 4v-2h2v2zm0 4v-2h2v2zm12 0v-2h2V5h-2V3h6v2h-2v14h2v2z");
}

</style>
