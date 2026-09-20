<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg45pac-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg45pac-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:virus-off" /></template>
