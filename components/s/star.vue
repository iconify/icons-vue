<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_p0ysbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s_p0ysbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:star" /></template>
