<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee1e7zbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ee1e7zbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:star" /></template>
