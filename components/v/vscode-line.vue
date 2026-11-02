<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fen-6uanf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fen-6uanf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vscode-line" /></template>
