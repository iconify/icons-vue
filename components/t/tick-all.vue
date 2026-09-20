<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt1y1kpfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt1y1kpfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tick-all" /></template>
