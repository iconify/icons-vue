<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t79xncbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:radio-button-16-regular" /></template>
<style>
.t79xncbgd {
  fill: currentColor;
  d: path("M8 3a5 5 0 1 0 0 10A5 5 0 0 0 8 3M2 8a6 6 0 1 1 12 0A6 6 0 0 1 2 8");
}

</style>
