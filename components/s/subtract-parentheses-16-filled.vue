<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gp577nbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:subtract-parentheses-16-filled" /></template>
<style>
.gp577nbqp {
  fill: currentColor;
  d: path("M4.7 3.6a.75.75 0 1 0-.901-1.2A6.99 6.99 0 0 0 1 8a6.99 6.99 0 0 0 2.799 5.6a.75.75 0 0 0 .9-1.2A5.49 5.49 0 0 1 2.5 8a5.49 5.49 0 0 1 2.2-4.4m7.5-1.2a.75.75 0 1 0-.9 1.2A5.49 5.49 0 0 1 13.5 8a5.49 5.49 0 0 1-2.2 4.4a.75.75 0 1 0 .901 1.2A6.99 6.99 0 0 0 15 8a6.99 6.99 0 0 0-2.799-5.6M5.75 7.25a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5z");
}

</style>
