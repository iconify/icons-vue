<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3h-3_brx.css';
import '../../css/m/m4dy9ybsj.css';
import '../../css/h/hcrkhjb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c3h-3_brx"/><path class="m4dy9ybsj"/><path class="hcrkhjb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:school-20" /></template>
