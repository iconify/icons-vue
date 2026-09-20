<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="blozd537p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-smoking-16-regular" /></template>
<style>
.blozd537p {
  fill: currentColor;
  d: path("M3.05 3.05a7 7 0 1 1 9.9 9.9a7 7 0 0 1-9.9-9.9M8.707 8H11.5a.5.5 0 0 1 .5.5V9a.5.5 0 0 1-.5.5H7.208l-3.082 3.082a6 6 0 0 0 8.457-8.456zm3.167-4.582a6 6 0 0 0-8.456 8.456L6 9.294V8h1.294zM5 9.5h-.5A.5.5 0 0 1 4 9v-.5a.5.5 0 0 1 .5-.5H5zm0-5.365c0-.158.214-.208.285-.067l.407.814a.69.69 0 0 1-.309.927a.69.69 0 0 0-.383.618v.798c0 .218-.286.297-.398.11l-.47-.784a.984.984 0 0 1 .533-1.44A.49.49 0 0 0 5 4.645z");
}

</style>
