<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rihgeqb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rihgeqb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:soil-moisture-field" /></template>
