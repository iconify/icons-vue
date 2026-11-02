<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzvic1rda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-alt-fill-round" /></template>
<style>
.jzvic1rda {
  fill: currentColor;
  d: path("m3.293 15.293l10-10a3.828 3.828 0 0 1 5.414 5.414l-10 10A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1v-4c0-.265.105-.52.293-.707");
}

</style>
