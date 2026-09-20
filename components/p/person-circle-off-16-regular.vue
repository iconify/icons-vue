<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fvcn_tmkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-off-16-regular" /></template>
<style>
.fvcn_tmkx {
  fill: currentColor;
  d: path("M1.146 1.146a.5.5 0 0 1 .708 0l13 13l.064.079a.5.5 0 0 1-.693.693l-.079-.064l-1.564-1.565A7 7 0 0 1 2.71 3.417L1.146 1.854a.5.5 0 0 1 0-.708m2.273 2.98a6 6 0 0 0 8.454 8.454l-1.02-1.02c-.548.555-1.47.94-2.853.94c-2.5 0-3.5-1.25-3.5-2.5A1.5 1.5 0 0 1 6 8.5h1.793zM8 1a7 7 0 0 1 5.895 10.773l-.727-.726A6 6 0 0 0 4.952 2.83l-.726-.727A6.97 6.97 0 0 1 8 1m0 2.5a2 2 0 0 1 2 2c0 .649-.311 1.223-.79 1.589l-2.8-2.8A2 2 0 0 1 8 3.5");
}

</style>
