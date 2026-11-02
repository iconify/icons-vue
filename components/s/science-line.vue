<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4l9t7zly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4l9t7zly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:science-line" /></template>
