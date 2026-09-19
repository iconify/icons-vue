<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whye44bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="whye44bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:temperature-water" /></template>
