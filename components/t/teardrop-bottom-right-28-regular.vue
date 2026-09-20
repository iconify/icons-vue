<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ckh412box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:teardrop-bottom-right-28-regular" /></template>
<style>
.ckh412box {
  fill: currentColor;
  d: path("M2 13.75C2 7.26 7.26 2 13.75 2h.5C20.74 2 26 7.26 26 13.75v9.5A2.75 2.75 0 0 1 23.25 26h-9.5C7.26 26 2 20.74 2 14.25zM13.75 3.5C8.09 3.5 3.5 8.09 3.5 13.75v.5c0 5.66 4.59 10.25 10.25 10.25h9.5c.69 0 1.25-.56 1.25-1.25v-9.5c0-5.66-4.59-10.25-10.25-10.25z");
}

</style>
