<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="aed4abibp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rectangle-portrait-28-regular" /></template>
<style>
.aed4abibp {
  fill: currentColor;
  d: path("M7.752 25.998a3.75 3.75 0 0 1-3.75-3.75V5.752a3.75 3.75 0 0 1 3.75-3.75h12.5a3.75 3.75 0 0 1 3.75 3.75v16.496a3.75 3.75 0 0 1-3.75 3.75zm-2.25-3.75a2.25 2.25 0 0 0 2.25 2.25h12.5a2.25 2.25 0 0 0 2.25-2.25V5.752a2.25 2.25 0 0 0-2.25-2.25h-12.5a2.25 2.25 0 0 0-2.25 2.25z");
}

</style>
