<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ifdehho8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-header-4-lines-caret-16-filled" /></template>
<style>
.ifdehho8t {
  fill: currentColor;
  d: path("M14.25 12.498a.75.75 0 0 1 0 1.5H1.75a.75.75 0 0 1 0-1.5zm0-2.998a.75.75 0 0 1 0 1.5H1.75a.75.75 0 0 1 0-1.5zM1.75 2a.75.75 0 0 1 .75.75v1.5h2V2.751a.75.75 0 0 1 1.5 0v4.496a.75.75 0 0 1-1.5 0V5.75h-2v1.5a.75.75 0 0 1-1.5 0v-4.5A.75.75 0 0 1 1.75 2m7.91.287A.75.75 0 0 1 11 2.75V5.5h.25a.75.75 0 0 1 0 1.5H11v.25a.75.75 0 0 1-1.5 0V7h-2a.75.75 0 0 1-.59-1.213zM14.498 4a.502.502 0 0 1 .354.854l-1 1.001a.5.5 0 0 1-.708 0l-1.001-1A.5.5 0 0 1 12.497 4zM9.043 5.5H9.5v-.582z");
}

</style>
