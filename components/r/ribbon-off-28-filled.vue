<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="vwahcdjzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ribbon-off-28-filled" /></template>
<style>
.vwahcdjzt {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l22.5 22.5a.75.75 0 0 1-1.06 1.06L20 21.06v4.19a.75.75 0 0 1-1.166.624L14 22.651l-4.834 3.223A.75.75 0 0 1 8 25.25v-7.386A9.46 9.46 0 0 0 14 20a9.45 9.45 0 0 0 4.037-.902l-.757-.757A8.5 8.5 0 0 1 6.158 7.219L2.22 3.28a.75.75 0 0 1 0-1.06M14 2a8.5 8.5 0 0 1 8.5 8.5a8.47 8.47 0 0 1-2.652 6.165L7.834 4.651A8.48 8.48 0 0 1 14 2");
}

</style>
