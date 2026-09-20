<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi-az1bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi-az1bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:sending-outlined" /></template>
