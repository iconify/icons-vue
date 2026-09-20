<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="m60y6xqcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tv-28-regular" /></template>
<style>
.m60y6xqcg {
  fill: currentColor;
  d: path("M5.254 4a3.25 3.25 0 0 0-3.25 3.25v10.5A3.25 3.25 0 0 0 5.254 21h17.497a3.25 3.25 0 0 0 3.25-3.25V7.25A3.25 3.25 0 0 0 22.751 4zm-1.75 3.25c0-.966.784-1.75 1.75-1.75h17.497c.966 0 1.75.784 1.75 1.75v10.5a1.75 1.75 0 0 1-1.75 1.75H5.254a1.75 1.75 0 0 1-1.75-1.75zM6.75 23a.75.75 0 0 0 0 1.5h14.5a.75.75 0 0 0 0-1.5z");
}

</style>
