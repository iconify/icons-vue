<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k9xr37bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-16-filled" /></template>
<style>
.k9xr37bch {
  fill: currentColor;
  d: path("M5.82 2.275c.956-1.7 3.404-1.7 4.36 0l4.496 8.004c.936 1.667-.269 3.725-2.18 3.725H3.503c-1.911 0-3.115-2.058-2.179-3.725zM8 9.5A.75.75 0 1 0 8 11a.75.75 0 0 0 0-1.5M8 5a.5.5 0 0 0-.5.5V8a.5.5 0 0 0 1 0V5.5A.5.5 0 0 0 8 5");
}

</style>
