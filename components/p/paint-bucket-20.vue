<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzzrqibpu.css';
import '../../css/i/ilum5ccux.css';
import '../../css/r/rtzhn3bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tzzrqibpu"/><path class="ilum5ccux"/><path class="rtzhn3bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paint-bucket-20" /></template>
