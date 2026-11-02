<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnmkwk03i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-line-alt-fill" /></template>
<style>
.rnmkwk03i {
  fill: currentColor;
  d: path("M3 16c0-.265.105-.52.293-.707l11-11a2.414 2.414 0 0 1 3.414 0l2 2a2.414 2.414 0 0 1 0 3.414L10.414 19H20a1 1 0 0 1 0 2H4a1 1 0 0 1-1-1Z");
}

</style>
