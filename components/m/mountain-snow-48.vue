<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slbli-wlk.css';
import '../../css/t/tys-9ybqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="slbli-wlk"/><path class="tys-9ybqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mountain-snow-48" /></template>
