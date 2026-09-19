<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3imq2azo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j3imq2azo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:paint-brush-20-solid" /></template>
