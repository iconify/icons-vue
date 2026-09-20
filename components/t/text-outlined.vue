<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4l3s8_di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4l3s8_di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:text-outlined" /></template>
