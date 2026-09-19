<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvsd7b6gz"/><path class="mkrz98btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-schedule-send" /></template>
<style>
.mkrz98btd {
  fill: currentColor;
  d: path("M17 12c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5m1.29 7l-1.65-1.65a.5.5 0 0 1-.15-.35v-2.5c0-.28.22-.5.5-.5s.5.22.5.5v2.29l1.5 1.5c.2.2.2.51 0 .71c-.19.2-.5.2-.7 0");
}

.xvsd7b6gz {
  fill: currentColor;
  d: path("M17 10c.1 0 .19.01.28.01L4.39 4.58C3.73 4.31 3 4.79 3 5.51v3.71c0 .46.31.86.76.97L11 12l-7.24 1.81c-.45.11-.76.51-.76.97v3.71c0 .72.73 1.2 1.39.92L10 17.05V17c0-3.86 3.14-7 7-7");
}

</style>
