<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn7-mf9wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-timeline-sharp" /></template>
<style>
.kn7-mf9wj {
  fill: currentColor;
  d: path("M4 20V4h16v16zm2.539-3.5h4.923v-1H6.539zm6-8h4.923v-1h-4.923zm-3 4h4.923v-1H9.539z");
}

</style>
