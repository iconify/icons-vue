<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzip_vo3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zzip_vo3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:windsurf-dark" /></template>
