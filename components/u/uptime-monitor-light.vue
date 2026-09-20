<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs-a7_bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zs-a7_bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptime-monitor-light" /></template>
