<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6r-gxbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="y6r-gxbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:th" /></template>
