<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktcjmyg5d.css';
import '../../css/i/isi39nobh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktcjmyg5d"/><path class="isi39nobh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:whatsapp-square" /></template>
