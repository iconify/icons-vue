<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="keqe71bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ticket-20-filled" /></template>
<style>
.keqe71bob {
  d: path("M18 6v1.5a.5.5 0 0 1-.5.5a2 2 0 1 0 0 4a.5.5 0 0 1 .5.5V14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-1.5a.5.5 0 0 1 .5-.5a2 2 0 1 0 0-4a.5.5 0 0 1-.5-.5V6a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1z");
  fill: currentColor;
  fill-rule: nonzero;
}

</style>
