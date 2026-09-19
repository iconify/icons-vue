<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3wwhbp_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="d3wwhbp_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-instagram" /></template>
