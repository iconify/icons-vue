<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra9pitbyh.css';
import '../../css/d/dwr76qb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ra9pitbyh"/><path class="dwr76qb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:t-alt" /></template>
