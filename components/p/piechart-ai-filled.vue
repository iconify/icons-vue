<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgm_8n2wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgm_8n2wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:piechart-ai-filled" /></template>
