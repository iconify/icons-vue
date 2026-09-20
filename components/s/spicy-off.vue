<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf9u4htgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf9u4htgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:spicy-off" /></template>
