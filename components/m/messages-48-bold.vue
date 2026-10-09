<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wan7vd7uu.css';
import '../../css/m/m_3bu7b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wan7vd7uu"/><path class="m_3bu7b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:messages-48-bold" /></template>
