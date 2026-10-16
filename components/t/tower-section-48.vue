<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnwg1wboc.css';
import '../../css/f/fu_1idbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qnwg1wboc"/><path class="fu_1idbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tower-section-48" /></template>
