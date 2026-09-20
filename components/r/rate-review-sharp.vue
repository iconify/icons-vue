<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf91rvbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rate-review-sharp" /></template>
<style>
.cf91rvbus {
  fill: currentColor;
  d: path("M6.385 13.616h2.21l5.89-5.897l-2.173-2.21l-5.927 5.897zM12.3 8.689l-.95-.945l.965-.955l.916.95zm-.484 4.927h5.8v-1h-4.8zM3 20.077V3h18v14H6.077z");
}

</style>
