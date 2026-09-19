<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj7kwhbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zj7kwhbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:memory" /></template>
