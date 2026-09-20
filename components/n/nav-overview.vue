<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yna26d0th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yna26d0th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-overview" /></template>
