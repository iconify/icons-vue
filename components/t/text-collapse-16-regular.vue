<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vcvw12bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-collapse-16-regular" /></template>
<style>
.vcvw12bzu {
  fill: currentColor;
  d: path("M13.5 13a.5.5 0 0 1 0 1h-10a.5.5 0 0 1 0-1zm-9-8.5a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7M3 7.5a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zM13.5 9a.5.5 0 0 1 0 1h-4a.5.5 0 0 1 0-1zm0-3a.5.5 0 0 1 0 1h-4a.5.5 0 0 1 0-1zm0-4a.5.5 0 0 1 0 1h-10a.5.5 0 0 1 0-1z");
}

</style>
