<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p7ptf9eaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paycom" /></template>
<style>
.p7ptf9eaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h4a2 2 0 0 0 2-2v-23a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v13a2 2 0 0 1-2 2H26a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h12.5a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
