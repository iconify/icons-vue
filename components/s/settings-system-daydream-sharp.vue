<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubojjgnen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settings-system-daydream-sharp" /></template>
<style>
.ubojjgnen {
  fill: currentColor;
  d: path("M9 16h6.5q1.05 0 1.775-.725T18 13.5t-.725-1.775T15.5 11h-.05q-.2-1.275-1.113-2.137T12.15 8q-1.05 0-1.95.525T8.85 10h-.125q-1.175 0-1.95.9T6 13q0 1.25.875 2.125T9 16m-7 4V4h20v16z");
}

</style>
