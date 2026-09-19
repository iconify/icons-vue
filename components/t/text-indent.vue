<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck4m_fflq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ck4m_fflq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-indent" /></template>
