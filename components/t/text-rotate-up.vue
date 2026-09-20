<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut7tyrbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-rotate-up" /></template>
<style>
.ut7tyrbeh {
  fill: currentColor;
  d: path("M18.692 19.27h-1V5.376l-1.55 1.55l-.707-.708l2.757-2.757l2.77 2.757l-.72.708l-1.55-1.55zm-4.846-3.131L3.538 12.23v-1L13.846 7.4v1.016l-2.838 1.026v4.642l2.838 1.039zm-3.707-2.373V9.772L4.858 11.68v.1z");
}

</style>
