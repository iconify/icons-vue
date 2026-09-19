<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd_zei36r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nd_zei36r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:query-queue" /></template>
