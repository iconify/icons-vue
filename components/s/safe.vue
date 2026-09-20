<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d186mbb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d186mbb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:safe" /></template>
