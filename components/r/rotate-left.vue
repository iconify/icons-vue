<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf0f2gbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yf0f2gbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:rotate-left" /></template>
