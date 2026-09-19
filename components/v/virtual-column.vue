<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh21c1arq.css';
import '../../css/g/gin_3l1fi.css';
import '../../css/y/yzfdw0bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zh21c1arq"/><path class="gin_3l1fi"/><path class="yzfdw0bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:virtual-column" /></template>
