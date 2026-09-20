<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="brsp0wbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-20-filled" /></template>
<style>
.brsp0wbpr {
  fill: currentColor;
  d: path("M10 3a8 8 0 0 1 8 8a5 5 0 0 1-3 4.583V12a3 3 0 1 0-3 3h.5a.5.5 0 0 0 0-1H12a2 2 0 1 1 2-2v4a2 2 0 0 0 2 2h.5a.5.5 0 0 1 0 1H16a3 3 0 0 1-3-3h-1a3.98 3.98 0 0 1-2.645-1H5.5A3.5 3.5 0 0 1 2 11.5V11a8 8 0 0 1 8-8");
}

</style>
