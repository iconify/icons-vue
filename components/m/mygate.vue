<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ro5y-th1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mygate" /></template>
<style>
.ro5y-th1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5c2.21 0 4-1.79 4-4v-29c0-2.21-1.79-4-4-4h-29c-2.21 0-4 1.79-4 4v29c0 2.21 1.79 4 4 4h9.876v-9.25A4.624 4.624 0 0 1 24 37.874a4.624 4.624 0 0 1 4.624-4.624v9.25z");
}

</style>
