<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce_m_3btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ce_m_3btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:paper" /></template>
