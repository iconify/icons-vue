<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drw4f59_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drw4f59_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paint-brush-line" /></template>
