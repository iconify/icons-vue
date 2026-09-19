<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-u4xnbot.css';
import '../../css/o/oa5_b0b8m.css';
import '../../css/z/zq-0s9biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m-u4xnbot"/><path class="oa5_b0b8m"/><path class="zq-0s9biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:navaid-dme" /></template>
