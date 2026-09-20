<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="haf30yb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tag-add-16-filled" /></template>
<style>
.haf30yb3f {
  fill: currentColor;
  d: path("M1.587 6.314a1.99 1.99 0 0 0 0 2.822l3.296 3.28a2 2 0 0 0 .64.428a5.5 5.5 0 0 1 7.458-7.254L13 3.01A2 2 0 0 0 10.987 1l-3.25.014a2 2 0 0 0-1.41.584zM10 5a1 1 0 1 1 0-2a1 1 0 0 1 0 2m5 5.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V10H8.5a.5.5 0 0 0 0 1H10v1.5a.5.5 0 0 0 1 0V11h1.5a.5.5 0 0 0 0-1H11z");
}

</style>
