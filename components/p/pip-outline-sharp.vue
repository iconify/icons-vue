<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zls9t69hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pip-outline-sharp" /></template>
<style>
.zls9t69hr {
  fill: currentColor;
  d: path("M2 11V9h3.6L1.3 4.7l1.4-1.4L7 7.6V4h2v7zm2 9q-.825 0-1.412-.587T2 18v-5h2v5h8v2zm16-7V6h-9V4h9q.825 0 1.413.588T22 6v7zm-6 7v-5h8v5z");
}

</style>
