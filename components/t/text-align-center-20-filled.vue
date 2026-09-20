<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ps00cx4-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-center-20-filled" /></template>
<style>
.ps00cx4-q {
  fill: currentColor;
  d: path("M4 4.25a.75.75 0 0 1 .75-.75h10.5a.75.75 0 0 1 0 1.5H4.75A.75.75 0 0 1 4 4.25m-2 5a.75.75 0 0 1 .75-.75h14.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 9.25m4.75 4.25a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 0-1.5z");
}

</style>
