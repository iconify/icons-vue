<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_57g2bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="u_57g2bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:sword" /></template>
