<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7d30qbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-column-two-left-24-regular" /></template>
<style>
.t7d30qbll {
  fill: currentColor;
  d: path("M21 5.75a.75.75 0 0 0-.75-.75h-9.5a.75.75 0 0 0 0 1.5h9.5a.75.75 0 0 0 .75-.75m-13 0A.75.75 0 0 0 7.25 5h-3.5a.75.75 0 0 0 0 1.5h3.5A.75.75 0 0 0 8 5.75m13 4a.75.75 0 0 0-.75-.75h-9.5a.75.75 0 0 0 0 1.5h9.5a.75.75 0 0 0 .75-.75m-13 0A.75.75 0 0 0 7.25 9h-3.5a.75.75 0 0 0 0 1.5h3.5A.75.75 0 0 0 8 9.75m13 4a.75.75 0 0 0-.75-.75h-9.5a.75.75 0 0 0 0 1.5h9.5a.75.75 0 0 0 .75-.75m-13 0a.75.75 0 0 0-.75-.75h-3.5a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 .75-.75m13 4a.75.75 0 0 0-.75-.75h-9.5a.75.75 0 0 0 0 1.5h9.5a.75.75 0 0 0 .75-.75m-13 0a.75.75 0 0 0-.75-.75h-3.5a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 .75-.75");
}

</style>
