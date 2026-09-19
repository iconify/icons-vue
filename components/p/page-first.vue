<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxmn-r4xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cxmn-r4xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:page-first" /></template>
