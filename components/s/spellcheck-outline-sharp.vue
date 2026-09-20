<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbmry7bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:spellcheck-outline-sharp" /></template>
<style>
.cbmry7bbp {
  fill: currentColor;
  d: path("m14.1 22l-4.25-4.25l1.4-1.4l2.85 2.85l5.65-5.65l1.4 1.4zM3 16L7.85 3h2.35l4.85 13h-2.3l-1.15-3.3H6.35L5.2 16zm4.05-5.2h3.9l-1.9-5.4h-.1z");
}

</style>
