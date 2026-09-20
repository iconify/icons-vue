<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr9tu2tsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-error-24-filled" /></template>
<style>
.dr9tu2tsh {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-5.477 2A6.47 6.47 0 0 0 11 17.5c0 1.644.61 3.146 1.617 4.291q-1.204.21-2.617.21c-2.89 0-5.128-.657-6.69-2a3.75 3.75 0 0 1-1.306-2.844v-.907A2.25 2.25 0 0 1 4.254 14zm5.477 5.875a.625.625 0 1 0 0 1.25a.625.625 0 0 0 0-1.25m0-5.875a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 1 0v-4a.5.5 0 0 0-.5-.5M10 2.005a5 5 0 1 1 0 10a5 5 0 0 1 0-10");
}

</style>
