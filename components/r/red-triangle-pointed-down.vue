<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nvtqfobhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:red-triangle-pointed-down" /></template>
<style>
.nvtqfobhl {
  fill: currentColor;
  d: path("M32 62L62 2H2z");
}

</style>
