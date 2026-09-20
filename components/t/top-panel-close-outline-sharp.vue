<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmow40x-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:top-panel-close-outline-sharp" /></template>
<style>
.mmow40x-m {
  fill: currentColor;
  d: path("M8 16.5h8l-4-4zM5 8h14V5H5zm0 11h14v-9H5zM5 8V5zM3 21V3h18v18z");
}

</style>
