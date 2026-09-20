<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp935in3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kp935in3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:watch-circle-heartbeat-monitor-1-solid" /></template>
