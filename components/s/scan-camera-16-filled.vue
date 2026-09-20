<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wk6cwr3yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:scan-camera-16-filled" /></template>
<style>
.wk6cwr3yp {
  fill: currentColor;
  d: path("M3.5 2.5a1 1 0 0 0-1 1v.75a.75.75 0 0 1-1.5 0V3.5A2.5 2.5 0 0 1 3.5 1h.75a.75.75 0 0 1 0 1.5zm0 11a1 1 0 0 1-1-1v-.75a.75.75 0 0 0-1.5 0v.75A2.5 2.5 0 0 0 3.5 15h.75a.75.75 0 0 0 0-1.5zm10-10a1 1 0 0 0-1-1h-.75a.75.75 0 0 1 0-1.5h.75A2.5 2.5 0 0 1 15 3.5v.75a.75.75 0 0 1-1.5 0zm-1 10a1 1 0 0 0 1-1v-.75a.75.75 0 0 1 1.5 0v.75a2.5 2.5 0 0 1-2.5 2.5h-.75a.75.75 0 0 1 0-1.5zm-8-6.115V10a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1V7.385a1 1 0 0 0-1-1h-.75l-.58-.92A1 1 0 0 0 8.323 5h-.648a1 1 0 0 0-.845.466l-.581.919H5.5a1 1 0 0 0-1 1M9 8.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

</style>
