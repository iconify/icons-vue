<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_0pmlbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-line-alt-fill-round" /></template>
<style>
.h_0pmlbhk {
  fill: currentColor;
  d: path("M3 16c0-.265.105-.52.293-.707l10-10a3.828 3.828 0 0 1 5.414 5.414L10.414 19H20a1 1 0 0 1 0 2H4a1 1 0 0 1-1-1Z");
}

</style>
