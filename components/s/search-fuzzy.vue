<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uowvmlswa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uowvmlswa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:search-fuzzy" /></template>
