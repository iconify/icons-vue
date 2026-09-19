<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5cbxjbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c5cbxjbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:prl" /></template>
