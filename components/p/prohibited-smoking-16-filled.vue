<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pnmhzpbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-smoking-16-filled" /></template>
<style>
.pnmhzpbmm {
  fill: currentColor;
  d: path("M3.05 3.05a7 7 0 1 1 9.9 9.9a7 7 0 0 1-9.9-9.9M9.061 8h2.438a.5.5 0 0 1 .5.5V9a.5.5 0 0 1-.5.5H7.561l-2.884 2.883a5.5 5.5 0 0 0 7.706-7.706zm2.262-4.383a5.501 5.501 0 0 0-7.706 7.706L5.999 8.94V8h.94zM4.999 9.5h-.5A.5.5 0 0 1 4 9v-.5a.5.5 0 0 1 .5-.5H5zm0-5.365c0-.158.214-.208.285-.067l.407.814a.69.69 0 0 1-.309.927a.69.69 0 0 0-.383.618v.798c0 .218-.286.297-.398.11l-.47-.784a.984.984 0 0 1 .533-1.44a.49.49 0 0 0 .335-.466z");
}

</style>
