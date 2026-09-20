<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vboiq-pvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vboiq-pvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:sort-left" /></template>
