<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoifu0ksb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qoifu0ksb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-4-ai-line" /></template>
