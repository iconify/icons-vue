<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="y9o3r9d-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:stack-vertical-28-regular" /></template>
<style>
.y9o3r9d-u {
  fill: currentColor;
  d: path("M21.25 3A3.75 3.75 0 0 1 25 6.75v17.5a.75.75 0 0 1-1.5 0v-5.5a2.25 2.25 0 0 0-2.25-2.25H6.75a2.25 2.25 0 0 0-2.25 2.25v5.5a.75.75 0 0 1-1.5 0V6.75A3.75 3.75 0 0 1 6.75 3zm-14.5 7.5a2.25 2.25 0 0 0-2.25 2.25v2.999A3.73 3.73 0 0 1 6.75 15h14.5c.844 0 1.623.278 2.25.749V12.75a2.25 2.25 0 0 0-2.25-2.25zm0-6A2.25 2.25 0 0 0 4.5 6.75v2.999A3.73 3.73 0 0 1 6.75 9h14.5c.844 0 1.623.278 2.25.749V6.75a2.25 2.25 0 0 0-2.25-2.25z");
}

</style>
