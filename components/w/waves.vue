<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zborlrgiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zborlrgiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:waves" /></template>
