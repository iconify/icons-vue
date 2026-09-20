<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="z01dxd9ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:zoom-out-28-filled" /></template>
<style>
.z01dxd9ir {
  fill: currentColor;
  d: path("M11.5 2a9.5 9.5 0 0 1 9.5 9.5a9.46 9.46 0 0 1-2.275 6.164l6.055 6.056a.75.75 0 1 1-1.06 1.06l-6.056-6.055A9.46 9.46 0 0 1 11.5 21a9.5 9.5 0 0 1 0-19m-3.75 8.75a.75.75 0 0 0 0 1.5h7.5a.75.75 0 0 0 0-1.5z");
}

</style>
