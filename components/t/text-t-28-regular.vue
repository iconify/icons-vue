<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="n4gg8qhbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-t-28-regular" /></template>
<style>
.n4gg8qhbt {
  fill: currentColor;
  d: path("M5 4.75A.75.75 0 0 1 5.75 4h16.5a.75.75 0 0 1 .75.75v3.5a.75.75 0 0 1-1.5 0V5.5h-6.75v17h1.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5h1.5v-17H6.5v2.75a.75.75 0 0 1-1.5 0z");
}

</style>
