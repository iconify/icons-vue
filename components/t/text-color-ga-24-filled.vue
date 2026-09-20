<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t795e87by"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-color-ga-24-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.t795e87by {
  d: path("M15.5 3.25a.75.75 0 0 0-1.5 0v8.5a.75.75 0 0 0 1.5 0V8H17a.75.75 0 0 0 0-1.5h-1.5V3.25zm-8.75.25a.75.75 0 1 0 0 1.5h4.245c-.162 1.634-1.328 4.092-4.46 5.032a.75.75 0 0 0 .43 1.436c4.39-1.317 5.726-5.15 5.532-7.286a.75.75 0 0 0-.747-.682h-5zM20 16.75a2.25 2.25 0 0 0-2.25-2.25H5.25A2.25 2.25 0 0 0 3 16.75v3A2.25 2.25 0 0 0 5.25 22h12.5A2.25 2.25 0 0 0 20 19.75v-3z");
  fill: currentColor;
}

</style>
