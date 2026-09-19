<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhd17n_ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jhd17n_ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-short-paragraph" /></template>
