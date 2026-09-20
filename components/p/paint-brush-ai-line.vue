<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi1ootbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi1ootbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paint-brush-ai-line" /></template>
