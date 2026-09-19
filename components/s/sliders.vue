<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_lfuxbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j_lfuxbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sliders" /></template>
