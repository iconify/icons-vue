<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dxs3_thzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:white-small-square" /></template>
<style>
.dxs3_thzc {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M16 16h32v32H16z");
}

</style>
