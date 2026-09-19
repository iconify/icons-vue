<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs367gbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fs367gbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plug-fill-16" /></template>
