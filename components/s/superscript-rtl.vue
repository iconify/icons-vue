<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvi_qzbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cvi_qzbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:superscript-rtl" /></template>
