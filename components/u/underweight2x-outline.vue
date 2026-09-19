<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i832tbe8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i832tbe8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:underweight2x-outline" /></template>
