<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g4kco4bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobily" /></template>
<style>
.g4kco4bpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 29.161V9.899a2.54 2.54 0 0 1 2.54-2.54h31.92a2.54 2.54 0 0 1 2.54 2.54v20.62a.98.98 0 0 1-1.435.865l-6.412-3.377a2.15 2.15 0 0 1-1.146-1.899v-8.212c0-.891-.722-1.613-1.613-1.613H16.38c-.89 0-1.613.722-1.613 1.613v8.546l26.817 12.39c1.05.485.477 2.071-.641 1.772l-33.56-8.99A2.54 2.54 0 0 1 5.5 29.161");
}

</style>
