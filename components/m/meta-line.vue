<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysx3eabub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysx3eabub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:meta-line" /></template>
