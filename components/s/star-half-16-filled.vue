<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ae_5qab2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-half-16-filled" /></template>
<style>
.ae_5qab2x {
  fill: currentColor;
  d: path("M8 1.6a.89.89 0 0 0-.806.501L5.673 5.183l-3.401.495a.9.9 0 0 0-.5 1.535l2.462 2.399l-.581 3.387a.9.9 0 0 0 1.306.949L8 12.349z");
}

</style>
