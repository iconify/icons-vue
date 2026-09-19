<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd95mviva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zd95mviva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pan-vertical" /></template>
