<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgdr8_b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgdr8_b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sea-waves-solid" /></template>
