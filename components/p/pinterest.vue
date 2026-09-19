<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt6m_qdhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="mt6m_qdhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:pinterest" /></template>
