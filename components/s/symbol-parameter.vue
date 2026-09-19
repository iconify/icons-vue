<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onx-m_b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="onx-m_b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-parameter" /></template>
