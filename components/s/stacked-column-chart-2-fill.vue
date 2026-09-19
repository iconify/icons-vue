<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fie42-j_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fie42-j_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:stacked-column-chart-2-fill" /></template>
