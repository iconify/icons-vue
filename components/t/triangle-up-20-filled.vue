<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cujrrmwdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-up-20-filled" /></template>
<style>
.cujrrmwdk {
  fill: currentColor;
  d: path("M11.32 2.785c-.568-1.047-2.071-1.047-2.638 0l-6.5 12a1.5 1.5 0 0 0 1.32 2.214H16.5a1.5 1.5 0 0 0 1.319-2.215z");
}

</style>
