<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmvw8i9yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-remove-done" /></template>
<style>
.kmvw8i9yi {
  fill: currentColor;
  d: path("M4.84 1.98L3.43 3.39l10.38 10.38l-1.41 1.41l-4.24-4.24l-1.41 1.41l5.66 5.66l2.83-2.83l6.6 6.6l1.41-1.41zm13.21 10.38L23 7.4L21.57 6l-4.94 4.94zm-.71-4.96l-1.41-1.41l-2.12 2.12l1.41 1.41zM1.08 12.35l5.66 5.66l1.41-1.41l-5.66-5.66z");
}

</style>
