<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy8533erf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zy8533erf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:upload" /></template>
