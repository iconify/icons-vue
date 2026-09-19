<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg38nmbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg38nmbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:search-plus-filled" /></template>
