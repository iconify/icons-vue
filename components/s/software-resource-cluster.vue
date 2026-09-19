<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm6b_0xno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pm6b_0xno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:software-resource-cluster" /></template>
