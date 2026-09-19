<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz1f_7svg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uz1f_7svg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:reply" /></template>
