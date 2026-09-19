<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4xm4bbzh.css';
import '../../css/i/im3qhl2-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w4xm4bbzh"/><path class="im3qhl2-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:product" /></template>
