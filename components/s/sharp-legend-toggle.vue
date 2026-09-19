<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6nb14bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-legend-toggle" /></template>
<style>
.q6nb14bed {
  fill: currentColor;
  d: path("M20 15H4v-2h16zm0 2H4v2h16zm-5-6l5-3.55V5l-5 3.55L10 5L4 8.66V11l5.92-3.61z");
}

</style>
