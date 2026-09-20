<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygt3p0bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygt3p0bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:slope-uphill" /></template>
