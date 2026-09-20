<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axg5usbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="axg5usbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:report-barchart" /></template>
