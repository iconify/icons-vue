<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zth73zbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zth73zbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:star3off" /></template>
