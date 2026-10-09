<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3dl8_bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e3dl8_bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scan-face-20-bold" /></template>
