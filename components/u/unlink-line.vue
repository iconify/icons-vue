<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb0pgvzvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb0pgvzvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unlink-line" /></template>
