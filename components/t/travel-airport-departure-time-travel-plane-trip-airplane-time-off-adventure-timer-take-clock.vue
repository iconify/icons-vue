<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgrhv-byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mgrhv-byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-airport-departure-time-travel-plane-trip-airplane-time-off-adventure-timer-take-clock" /></template>
