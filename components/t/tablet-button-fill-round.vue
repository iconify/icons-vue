<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akpibvbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tablet-button-fill-round" /></template>
<style>
.akpibvbqe {
  fill: currentColor;
  d: path("M3 7a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5Zm9.01 10H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
