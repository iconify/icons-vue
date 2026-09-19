<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm396wb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-feedback" /></template>
<style>
.wm396wb7t {
  fill: currentColor;
  d: path("M22 2H2.01L2 22l4-4h16zm-9 12h-2v-2h2zm0-4h-2V6h2z");
}

</style>
