<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l4dcppbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-16-regular" /></template>
<style>
.l4dcppbne {
  fill: currentColor;
  d: path("M7 12a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zM5.75 1A1.75 1.75 0 0 0 4 2.75v10.5c0 .966.784 1.75 1.75 1.75h4.5A1.75 1.75 0 0 0 12 13.25V2.75A1.75 1.75 0 0 0 10.25 1zM5 2.75A.75.75 0 0 1 5.75 2h4.5a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-.75.75h-4.5a.75.75 0 0 1-.75-.75z");
}

</style>
