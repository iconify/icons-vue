<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="z8oob-b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-28-filled" /></template>
<style>
.z8oob-b2b {
  fill: currentColor;
  d: path("M10.742 4.897c1.438-2.529 5.083-2.529 6.52 0L25.506 19.4c1.42 2.5-.385 5.602-3.26 5.603H5.76c-2.875 0-4.68-3.103-3.26-5.603zM14.002 18a1 1 0 1 0 0 2a1 1 0 0 0 0-2m0-9a.75.75 0 0 0-.75.75v6a.75.75 0 0 0 1.5 0v-6a.75.75 0 0 0-.75-.75");
}

</style>
