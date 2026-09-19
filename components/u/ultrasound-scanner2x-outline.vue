<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxfyeibqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vxfyeibqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ultrasound-scanner2x-outline" /></template>
