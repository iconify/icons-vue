<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f_l28bd7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-column-two-20-filled" /></template>
<style>
.f_l28bd7p {
  fill: currentColor;
  d: path("M17 5.75a.75.75 0 0 0-.75-.75h-4.5a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 .75-.75m-8 0A.75.75 0 0 0 8.25 5h-4.5a.75.75 0 0 0 0 1.5h4.5A.75.75 0 0 0 9 5.75m8 3a.75.75 0 0 0-.75-.75h-4.5a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 .75-.75m-8 0A.75.75 0 0 0 8.25 8h-4.5a.75.75 0 0 0 0 1.5h4.5A.75.75 0 0 0 9 8.75m8 3a.75.75 0 0 0-.75-.75h-4.5a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 .75-.75m-8 0a.75.75 0 0 0-.75-.75h-4.5a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 .75-.75m8 3a.75.75 0 0 0-.75-.75h-4.5a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 .75-.75m-8 0a.75.75 0 0 0-.75-.75h-4.5a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 .75-.75");
}

</style>
