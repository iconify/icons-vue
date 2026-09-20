<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hcl23zthw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-16-regular" /></template>
<style>
.hcl23zthw {
  fill: currentColor;
  d: path("M10.5 1A2.5 2.5 0 0 1 13 3.5v9a2.5 2.5 0 0 1-2.5 2.5h-5A2.5 2.5 0 0 1 3 12.5v-9A2.5 2.5 0 0 1 5.5 1zm-5 1A1.5 1.5 0 0 0 4 3.5v9A1.5 1.5 0 0 0 5.5 14h5a1.5 1.5 0 0 0 1.5-1.5v-9A1.5 1.5 0 0 0 10.5 2zM6 6.751a1 1 0 0 1 1.528-.849L9.53 7.15a1 1 0 0 1 0 1.698l-2 1.246A1 1 0 0 1 6 9.244z");
}

</style>
