<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="feqki8b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-lock-open-20-filled" /></template>
<style>
.feqki8b8q {
  fill: currentColor;
  d: path("M18 10a2 2 0 0 1 2 2a.5.5 0 0 1-1 0a1 1 0 0 0-2 0v1h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h3v-1a2 2 0 0 1 2-2M7.37 3.556c1.14-2.074 4.12-2.074 5.259 0l3.398 6.186A3 3 0 0 0 15 12h-2a2 2 0 0 0-2 2v4.005H4.504c-2.281 0-3.727-2.445-2.629-4.444zM15.5 15.25a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m-5.5-2.5a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m0-6.25a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 1 0V7a.5.5 0 0 0-.5-.5");
}

</style>
