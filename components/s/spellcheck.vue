<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob15n2bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:spellcheck" /></template>
<style>
.ob15n2bin {
  fill: currentColor;
  d: path("M12.45 16h2.09L9.43 3H7.57L2.46 16h2.09l1.12-3h5.64zm-6.02-5L8.5 5.48L10.57 11zm15.16.59l-8.09 8.09L9.83 16l-1.41 1.41l5.09 5.09L23 13z");
}

</style>
