<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qogk-zxfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qogk-zxfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:text-align-justify" /></template>
