<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb3ll9hft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb3ll9hft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-dashed-line" /></template>
