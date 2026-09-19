<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_c4xabtr.css';
import '../../css/t/t9axjb05q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a_c4xabtr"/><path class="t9axjb05q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:part-definition" /></template>
