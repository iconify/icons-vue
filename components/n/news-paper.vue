<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc6imzbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hc6imzbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:news-paper" /></template>
