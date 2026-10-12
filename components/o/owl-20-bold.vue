<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2w_usb8e.css';
import '../../css/p/p0fmtdpyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t2w_usb8e"/><path class="p0fmtdpyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:owl-20-bold" /></template>
