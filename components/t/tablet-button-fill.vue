<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_arm0b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tablet-button-fill" /></template>
<style>
.w_arm0b1o {
  fill: currentColor;
  d: path("M3 5a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Zm9.01 12H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
