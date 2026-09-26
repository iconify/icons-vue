<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dzcujybck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-collapse-20-regular" /></template>
<style>
.dzcujybck {
  fill: currentColor;
  d: path("M17.5 15a.5.5 0 0 1 0 1h-14a.5.5 0 0 1 0-1zm-13-9a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7M2.75 9a.5.5 0 0 0 0 1h3.5a.5.5 0 0 0 0-1zm14.75 2a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1zm0-4a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1zm0-4a.5.5 0 0 1 0 1h-14a.5.5 0 0 1 0-1z");
}

</style>
