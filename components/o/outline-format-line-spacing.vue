<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="siskydbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-format-line-spacing" /></template>
<style>
.siskydbba {
  fill: currentColor;
  d: path("M6 7h2.5L5 3.5L1.5 7H4v10H1.5L5 20.5L8.5 17H6zm4-2v2h12V5zm0 14h12v-2H10zm0-6h12v-2H10z");
}

</style>
