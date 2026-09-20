<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs-u90x8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vs-u90x8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pen" /></template>
