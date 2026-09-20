<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyrkybcgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyrkybcgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:smart-home-sharp" /></template>
