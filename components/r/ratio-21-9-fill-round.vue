<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq1ge0_ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ratio-21-9-fill-round" /></template>
<style>
.aq1ge0_ym {
  fill: currentColor;
  d: path("M7 7h10a5 5 0 0 1 0 10H7A5 5 0 0 1 7 7");
}

</style>
