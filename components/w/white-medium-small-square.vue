<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nd4ph-hjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:white-medium-small-square" /></template>
<style>
.nd4ph-hjk {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M12 12h40v40H12z");
}

</style>
