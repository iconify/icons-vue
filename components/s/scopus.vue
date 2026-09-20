<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyst4hbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zyst4hbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:scopus" /></template>
