<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b305n0b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sports-hockey-outline-sharp" /></template>
<style>
.b305n0b_b {
  fill: currentColor;
  d: path("M2 20v-4h2v4zm3 0v-4h4l.85-1.95l1.6 3.5l-1.1 2.45zm15 0v-4h2v4zm-1 0h-5.35L6.35 4H9.7L12 9.2L14.3 4h3.35l-4.05 8.85L15 16h4z");
}

</style>
