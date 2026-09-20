<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="otahkbioe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:speaker-box-16-filled" /></template>
<style>
.otahkbioe {
  fill: currentColor;
  d: path("M3 3.5A2.5 2.5 0 0 1 5.5 1h5A2.5 2.5 0 0 1 13 3.5v9a2.5 2.5 0 0 1-2.5 2.5h-5A2.5 2.5 0 0 1 3 12.5zM9 5a1 1 0 1 0-2 0a1 1 0 0 0 2 0m-2.5 5a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0M8 7.5a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5");
}

</style>
