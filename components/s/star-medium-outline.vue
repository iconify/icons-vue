<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rthdijk0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rthdijk0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:star-medium-outline" /></template>
