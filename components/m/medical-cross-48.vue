<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kirv6-xpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kirv6-xpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:medical-cross-48" /></template>
