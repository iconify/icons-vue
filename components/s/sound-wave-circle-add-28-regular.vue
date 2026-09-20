<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="q70ol54iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sound-wave-circle-add-28-regular" /></template>
<style>
.q70ol54iv {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13M14 2c6.627 0 12 5.373 12 12q0 .672-.073 1.325a7.5 7.5 0 0 0-1.432-1.17c0-.052.005-.103.005-.155c0-5.799-4.701-10.5-10.5-10.5S3.5 8.201 3.5 14S8.201 24.5 14 24.5l.154-.005a7.5 7.5 0 0 0 1.171 1.432q-.653.072-1.325.073C7.373 26 2 20.627 2 14S7.373 2 14 2m6.5 14a.5.5 0 0 0-.5.5V20h-3.5a.5.5 0 0 0 0 1H20v3.5a.5.5 0 0 0 1 0V21h3.5a.5.5 0 0 0 0-1H21v-3.5a.5.5 0 0 0-.5-.5m-8.25-7a.75.75 0 0 1 .75.75v8.5a.75.75 0 0 1-1.5 0v-8.5a.75.75 0 0 1 .75-.75m-3.5 2.5a.75.75 0 0 1 .75.75v3.5a.75.75 0 0 1-1.5 0v-3.5a.75.75 0 0 1 .75-.75m7-.5a.75.75 0 0 1 .75.75v2.407a7.5 7.5 0 0 0-1.5 1.245V11.75a.75.75 0 0 1 .75-.75m3.5-2a.75.75 0 0 1 .75.75v3.269a7.5 7.5 0 0 0-1.5.252V9.75a.75.75 0 0 1 .75-.75");
}

</style>
