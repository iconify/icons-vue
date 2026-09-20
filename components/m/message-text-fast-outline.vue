<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgchb91wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgchb91wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-text-fast-outline" /></template>
