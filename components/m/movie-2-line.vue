<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzyj9h1zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzyj9h1zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:movie-2-line" /></template>
