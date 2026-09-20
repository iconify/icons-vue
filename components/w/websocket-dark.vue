<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3l2wxb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m3l2wxb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:websocket-dark" /></template>
