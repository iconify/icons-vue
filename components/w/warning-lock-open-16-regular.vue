<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hcz73e2sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-lock-open-16-regular" /></template>
<style>
.hcz73e2sb {
  fill: currentColor;
  d: path("M14 7a2 2 0 0 1 2 2a.5.5 0 1 1-1 0a1 1 0 1 0-2 0v1h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h3V9a2 2 0 0 1 2-2m-2.5 5.25a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M4.82 1.275c.956-1.7 3.404-1.7 4.36 0l3 5.342c-.28.215-.521.477-.711.776L8.307 1.765a1.5 1.5 0 0 0-2.615 0L1.195 9.769a1.5 1.5 0 0 0 1.308 2.235H7v1H2.503c-1.911 0-3.115-2.058-2.179-3.725zM7 8.5a.75.75 0 1 1-.001 1.5a.75.75 0 0 1 0-1.501M7 4a.5.5 0 0 1 .5.5V7a.5.5 0 0 1-1 0V4.5A.5.5 0 0 1 7 4");
}

</style>
