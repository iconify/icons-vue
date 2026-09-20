<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zijm3bbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zijm3bbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptime-monitor-dark" /></template>
