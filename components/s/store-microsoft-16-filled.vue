<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g-di7p17e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:store-microsoft-16-filled" /></template>
<style>
.g-di7p17e {
  fill: currentColor;
  d: path("M5 3.5V5H2.5a.5.5 0 0 0-.5.5V12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V5.5a.5.5 0 0 0-.5-.5H11V3.5A1.5 1.5 0 0 0 9.5 2h-3A1.5 1.5 0 0 0 5 3.5M6.5 3h3a.5.5 0 0 1 .5.5V5H6V3.5a.5.5 0 0 1 .5-.5m-1 6V7h2v2zm0 3v-2h2v2zm5-3h-2V7h2zm-2 3v-2h2v2z");
}

</style>
