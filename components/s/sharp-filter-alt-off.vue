<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fis-ukiiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-filter-alt-off" /></template>
<style>
.fis-ukiiq {
  fill: currentColor;
  d: path("M21.05 4H6.83l7.97 7.97zM2.81 2.81L1.39 4.22L10 13v7h4v-3.17l5.78 5.78l1.41-1.42z");
}

</style>
