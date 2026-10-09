<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhk2u_byh.css';
import '../../css/k/ke0ka4ymk.css';
import '../../css/v/vdxrn18am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zhk2u_byh"/><path class="ke0ka4ymk"/><path class="vdxrn18am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-wheel-48" /></template>
