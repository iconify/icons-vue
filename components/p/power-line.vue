<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j38ouxb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j38ouxb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:power-line" /></template>
