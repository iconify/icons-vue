<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktc_cwb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:rule-outline" /></template>
<style>
.ktc_cwb7d {
  fill: currentColor;
  d: path("M14.4 20L13 18.6l2.6-2.6l-2.6-2.6l1.4-1.4l2.6 2.6l2.6-2.6l1.4 1.4l-2.6 2.6l2.6 2.6l-1.4 1.4l-2.6-2.6zm1.975-9l-3.55-3.55l1.4-1.4l2.125 2.125l4.25-4.25L22 5.35zM2 17v-2h9v2zm0-8V7h9v2z");
}

</style>
