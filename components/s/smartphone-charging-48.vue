<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyz2fo8fs.css';
import '../../css/q/q372t5bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kyz2fo8fs"/><path class="q372t5bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smartphone-charging-48" /></template>
