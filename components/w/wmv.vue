<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amns9fbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="amns9fbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wmv" /></template>
