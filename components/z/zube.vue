<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":178};
const content = `<path class="ux5cdvbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:zube" /></template>
<style>
.ux5cdvbfh {
  fill: var(--svg-color--0d83dd, #0d83dd);
  d: path("m0 63.228l119.833 63.23v50.744L0 113.972zM119.834 0L8.994 58.483L57.08 83.855l62.754-33.111zm16.333 0v50.744L207.914 88.6l-71.747 37.856V177.2L256 113.971V63.229z");
}

</style>
