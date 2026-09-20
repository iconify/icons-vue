<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu5z-p6zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gu5z-p6zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:spiral-shape-solid" /></template>
