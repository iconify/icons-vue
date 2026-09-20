<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg5bd0bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screenshot-tablet-sharp" /></template>
<style>
.eg5bd0bty {
  fill: currentColor;
  d: path("M1 20V4h22v16zm5-2h12V6H6zm7-1h4v-4h-1.5v2.5H13zm-6-6h1.5V8.5H11V7H7z");
}

</style>
