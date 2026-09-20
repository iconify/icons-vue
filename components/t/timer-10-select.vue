<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyri9cc8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timer-10-select" /></template>
<style>
.qyri9cc8c {
  fill: currentColor;
  d: path("M10 16h3V8h-3zm0 3q-1.25 0-2.125-.875T7 16V8q0-1.25.875-2.125T10 5h3q1.25 0 2.125.875T16 8v8q0 1.25-.875 2.125T13 19zm-7 0V8H1V5h5v14zm14 0v-2h4v-1h-2.65q-.575 0-.962-.387T17 14.65v-2.3q0-.575.388-.962T18.35 11H23v2h-4v1h2.65q.575 0 .963.388t.387.962v2.3q0 .575-.387.963T21.65 19z");
}

</style>
