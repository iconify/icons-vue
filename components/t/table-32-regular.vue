<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t-nz0oxjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-32-regular" /></template>
<style>
.t-nz0oxjr {
  fill: currentColor;
  d: path("M4 9a5 5 0 0 1 5-5h14a5 5 0 0 1 5 5v14a5 5 0 0 1-5 5H9a5 5 0 0 1-5-5zm5-3a3 3 0 0 0-3 3v2h5V6zm4 0v5h6V6zm0 7v6h6v-6zm-2 6v-6H6v6zm-5 2v2a3 3 0 0 0 3 3h2v-5zm7 0v5h6v-5zm8 0v5h2a3 3 0 0 0 3-3v-2zm5-2v-6h-5v6zM21 6v5h5V9a3 3 0 0 0-3-3z");
}

</style>
