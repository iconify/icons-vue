<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh-648kaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh-648kaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:teespring" /></template>
