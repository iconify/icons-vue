<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-b4ufqaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d-b4ufqaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:presentation-chart-bar-20-solid" /></template>
