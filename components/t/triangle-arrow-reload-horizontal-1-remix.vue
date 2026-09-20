<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp3zy8coe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yp3zy8coe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:triangle-arrow-reload-horizontal-1-remix" /></template>
