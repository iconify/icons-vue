<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6_bndyut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p6_bndyut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:overlay" /></template>
