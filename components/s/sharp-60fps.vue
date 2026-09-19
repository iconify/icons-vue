<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh8ci2b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-60fps" /></template>
<style>
.fh8ci2b1g {
  fill: currentColor;
  d: path("M19 8v8h-4V8zm3-3H12v14h10zM10 8V5H2v14h9v-9H5V8zm-2 5v3H5v-3z");
}

</style>
