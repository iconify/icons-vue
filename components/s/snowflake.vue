<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmeq4wibs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pmeq4wibs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:snowflake" /></template>
