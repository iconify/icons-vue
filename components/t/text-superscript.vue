<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdzs-wbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tdzs-wbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-superscript" /></template>
