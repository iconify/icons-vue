<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dguxuj9xv.css';
import '../../css/h/hu6j50bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dguxuj9xv"/><path class="hu6j50bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:picture-in-picture" /></template>
