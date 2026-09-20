<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxgponvlu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxgponvlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:move-vertical" /></template>
