<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6r127bgj.css';
import '../../css/e/e7r56mbuj.css';
import '../../css/q/qs_8itbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6r127bgj"/><path class="e7r56mbuj"/><path class="qs_8itbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:messages-bubble-square-lock" /></template>
