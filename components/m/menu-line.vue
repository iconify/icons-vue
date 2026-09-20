<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzku5q1zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzku5q1zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:menu-line" /></template>
