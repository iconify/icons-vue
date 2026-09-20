<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gbsiygn_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slash-forward-12-regular" /></template>
<style>
.gbsiygn_p {
  fill: currentColor;
  d: path("M7.658 1.026a.5.5 0 0 1 .316.632l-3 9a.5.5 0 1 1-.948-.316l3-9a.5.5 0 0 1 .632-.316");
}

</style>
