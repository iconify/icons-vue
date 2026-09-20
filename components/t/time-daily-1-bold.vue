<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb5p6obzi.css';
import '../../css/o/ow-wen-ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb5p6obzi"/><path class="ow-wen-ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:time-daily-1-bold" /></template>
