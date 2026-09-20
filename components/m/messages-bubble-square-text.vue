<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6r127bgj.css';
import '../../css/z/zta7gebwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6r127bgj"/><path class="zta7gebwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:messages-bubble-square-text" /></template>
