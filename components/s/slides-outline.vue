<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi9btnbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:slides-outline" /></template>
<style>
.hi9btnbma {
  fill: currentColor;
  d: path("M7 19v-7h10v7Zm1.5-1.5h7v-4h-7ZM18 22H6q-.825 0-1.412-.587Q4 20.825 4 20V4q0-.825.588-1.413Q5.175 2 6 2h8l6 6v12q0 .825-.587 1.413Q18.825 22 18 22ZM13 9V4H6v16h12V9ZM6 9V4v16Z");
}

</style>
