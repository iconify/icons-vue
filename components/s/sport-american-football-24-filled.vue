<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnznzikpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sport-american-football-24-filled" /></template>
<style>
.mnznzikpm {
  fill: currentColor;
  d: path("M21.379 11.5a14.78 14.78 0 0 1-9.973 9.906l-8.812-8.812A14.78 14.78 0 0 1 12.5 2.62zm-7.66-2.28l-4.5 4.5a.75.75 0 1 0 1.061 1.06l4.5-4.5a.75.75 0 1 0-1.06-1.06M2.2 14.32l7.48 7.48q-1.186.2-2.43.2h-1A4.25 4.25 0 0 1 2 17.75v-1q.001-1.243.2-2.43M14.217 2.217l7.566 7.566q.216-1.236.217-2.533v-1A4.25 4.25 0 0 0 17.75 2h-1q-1.297.001-2.533.217");
}

</style>
