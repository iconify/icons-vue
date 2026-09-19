<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuvh9jb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zuvh9jb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:x-ray" /></template>
