<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znrnrgmtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="znrnrgmtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:slider-horizontal-48-bold" /></template>
