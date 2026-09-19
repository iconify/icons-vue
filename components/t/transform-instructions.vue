<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw068u8kk.css';
import '../../css/w/wx-066bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gw068u8kk"/><path class="wx-066bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:transform-instructions" /></template>
