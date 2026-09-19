<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npykxrbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="npykxrbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:person-gear" /></template>
