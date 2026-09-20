<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py02m_bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py02m_bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:news-fill" /></template>
