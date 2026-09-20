<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="orcbmacot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-off-16-filled" /></template>
<style>
.orcbmacot {
  fill: currentColor;
  d: path("M1.146 1.146a.5.5 0 0 1 .708 0l13 13l.064.079a.5.5 0 0 1-.693.693l-.079-.064l-1.564-1.565A7 7 0 0 1 2.71 3.417L1.146 1.854a.5.5 0 0 1 0-.708M6 8.5A1.5 1.5 0 0 0 4.5 10c0 1.25 1 2.5 3.5 2.5c1.383 0 2.305-.385 2.854-.94L7.793 8.5zM8 1a7 7 0 0 1 5.895 10.773L9.21 7.09c.479-.366.79-.94.79-1.589a2 2 0 0 0-3.59-1.21L4.226 2.103A6.97 6.97 0 0 1 8 1");
}

</style>
