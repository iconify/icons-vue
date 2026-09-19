<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp18axg0l"/><path class="o-7hg4bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-timer-off" /></template>
<style>
.kp18axg0l {
  fill: currentColor;
  d: path("M9 1h6v2H9zm3 5c3.87 0 7 3.13 7 7c0 .94-.19 1.83-.52 2.65l1.5 1.5a8.96 8.96 0 0 0-.95-9.76l1.42-1.42c-.43-.51-.9-.99-1.41-1.41l-1.42 1.42a8.96 8.96 0 0 0-9.77-.96l1.5 1.5A7.1 7.1 0 0 1 12 6");
}

.o-7hg4bwk {
  fill: currentColor;
  d: path("m11 8.17l2 2V8h-2zM2.81 2.81L1.39 4.22l3.4 3.4a8.994 8.994 0 0 0 12.59 12.59l2.4 2.4l1.41-1.41zM12 20c-3.87 0-7-3.13-7-7c0-1.47.45-2.83 1.22-3.95l9.73 9.73A6.95 6.95 0 0 1 12 20");
}

</style>
