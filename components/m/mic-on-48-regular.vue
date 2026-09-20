<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="ivu-lebsd"/><path class="lcq-efblc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mic-on-48-regular" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ivu-lebsd {
  d: path("M16 12a8 8 0 1 1 16 0v12a8 8 0 1 1-16 0V12zm8-5.5a5.5 5.5 0 0 0-5.5 5.5v12a5.5 5.5 0 1 0 11 0V12A5.5 5.5 0 0 0 24 6.5z");
  fill: currentColor;
}

.lcq-efblc {
  d: path("M25 37.715c7.265-.513 13-6.57 13-13.965a1.25 1.25 0 1 0-2.5 0c0 6.351-5.149 11.5-11.5 11.5s-11.5-5.149-11.5-11.5a1.25 1.25 0 1 0-2.5 0c0 7.225 5.473 13.172 12.5 13.92v5.08a1.25 1.25 0 1 0 2.5 0v-5.035z");
  fill: currentColor;
}

</style>
