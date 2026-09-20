<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv3b01bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv3b01bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-dashboard-outline" /></template>
