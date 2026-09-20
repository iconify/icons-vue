<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov1wd7b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov1wd7b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:text-align-left-box-sharp" /></template>
