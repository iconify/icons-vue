<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq0baacen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xq0baacen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-youtube" /></template>
