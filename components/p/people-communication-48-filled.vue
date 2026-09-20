<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="og9c1cd6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-communication-48-filled" /></template>
<style>
.og9c1cd6i {
  fill: currentColor;
  d: path("M26.222 27.222c4.295-4.296 11.26-4.296 15.556 0c4.296 4.295 4.296 11.26 0 15.556a1.25 1.25 0 0 1-1.768-1.767a8.5 8.5 0 1 0-12.02 0a1.25 1.25 0 0 1-1.768 1.767c-4.296-4.295-4.296-11.26 0-15.556m3.18 3.181a6.5 6.5 0 0 1 9.193 9.193a1.25 1.25 0 0 1-1.768-1.768a4 4 0 1 0-5.656 0a1.25 1.25 0 0 1-1.769 1.768a6.5 6.5 0 0 1 0-9.193M25.25 25q.212 0 .417.023A12.97 12.97 0 0 0 21 35c0 1.156.151 2.276.435 3.343c-1.497.41-3.288.657-5.435.657c-13 0-13-9-13-9v-1.25A3.75 3.75 0 0 1 6.75 25zM16 6a8 8 0 1 1 0 16a8 8 0 0 1 0-16m18 4a6 6 0 1 1 0 12a6 6 0 0 1 0-12");
}

</style>
