<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmokpm6wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmokpm6wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vscode-fill" /></template>
