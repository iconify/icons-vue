<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz55eabvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz55eabvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pdf-fill" /></template>
