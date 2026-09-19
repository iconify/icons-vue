<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pumg_ybch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-price-change" /></template>
<style>
.pumg_ybch {
  fill: currentColor;
  d: path("M2 4v16h20V4zm10 6H8v1h4v5h-2v1H8v-1H6v-2h4v-1H6V8h2V7h2v1h2zm4 6.25l-2-2h4zM14 10l2-2l2 2z");
}

</style>
