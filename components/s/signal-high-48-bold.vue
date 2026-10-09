<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-zi6-bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i-zi6-bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-high-48-bold" /></template>
