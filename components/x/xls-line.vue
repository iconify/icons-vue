<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbbh_ydme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbbh_ydme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:xls-line" /></template>
