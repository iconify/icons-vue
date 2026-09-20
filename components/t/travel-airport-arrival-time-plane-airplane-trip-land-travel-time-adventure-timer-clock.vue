<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwcwarblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hwcwarblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-airport-arrival-time-plane-airplane-trip-land-travel-time-adventure-timer-clock" /></template>
