<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ydyepe64d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:markdown-28-regular" /></template>
<style>
.ydyepe64d {
  fill: currentColor;
  d: path("M15.72 6.22a.75.75 0 0 1 1.28.53v13.5a.75.75 0 1 1-1.5 0V8.56l-4.97 4.97a.75.75 0 0 1-1.06 0L4.5 8.56v11.69a.75.75 0 0 1-1.5 0V6.75a.751.751 0 0 1 1.28-.53L10 11.94zM22.75 6a.75.75 0 0 1 .75.75v11.69l1.72-1.72a.75.75 0 0 1 1.06 1.06l-3 3a.75.75 0 0 1-1.06 0l-3-3a.75.75 0 0 1 1.06-1.06L22 18.44V6.75a.75.75 0 0 1 .75-.75");
}

</style>
