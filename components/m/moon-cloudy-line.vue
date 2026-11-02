<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el-0wrg4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el-0wrg4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moon-cloudy-line" /></template>
