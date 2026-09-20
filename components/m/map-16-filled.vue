<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lymp3m9ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:map-16-filled" /></template>
<style>
.lymp3m9ab {
  fill: currentColor;
  d: path("M5 2.223L1.235 4.576A.5.5 0 0 0 1 5v8.5a.5.5 0 0 0 .765.424L5 11.902zm1 9.586l4 2V4.191l-4-2zm8.765-.385L11 13.777v-9.68l3.235-2.021A.5.5 0 0 1 15 2.5V11a.5.5 0 0 1-.235.424");
}

</style>
