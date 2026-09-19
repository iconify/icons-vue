<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf0fdac8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-pause" /></template>
<style>
.rf0fdac8k {
  fill: currentColor;
  d: path("M6 5h4v14H6zm8 0h4v14h-4z");
}

</style>
