<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty51eibwy.css';
import '../../css/p/pg7d3m2ja.css';
import '../../css/y/ybvnaxjzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ty51eibwy"/><path class="pg7d3m2ja"/><path class="ybvnaxjzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:mic-off" /></template>
