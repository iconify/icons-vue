<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qesv06b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stat-minus-1-outline" /></template>
<style>
.qesv06b8h {
  fill: currentColor;
  d: path("m12 15.375l-6-6l1.4-1.4L12 12.55l4.6-4.575l1.4 1.4z");
}

</style>
