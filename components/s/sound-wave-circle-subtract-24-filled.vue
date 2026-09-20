<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy6uv5j2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sound-wave-circle-subtract-24-filled" /></template>
<style>
.qy6uv5j2m {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M12 2c5.523 0 10 4.477 10 10q-.002.393-.033.78A6.48 6.48 0 0 0 17 11.02V8.75a.75.75 0 0 0-1.5 0v2.565a6.5 6.5 0 0 0-1.5.71V10.25a.75.75 0 0 0-1.5 0v3.097A6.47 6.47 0 0 0 11 17.5c0 1.73.677 3.302 1.78 4.467q-.387.032-.78.033C6.477 22 2 17.523 2 12S6.477 2 12 2m2.495 15a.5.5 0 0 0 0 1h6.002a.5.5 0 0 0 0-1zM10.25 8a.75.75 0 0 0-.75.75v6.5a.75.75 0 0 0 1.5 0v-6.5a.75.75 0 0 0-.75-.75m-3 2a.75.75 0 0 0-.75.75v2.5a.75.75 0 0 0 1.5 0v-2.5a.75.75 0 0 0-.75-.75");
}

</style>
