<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gregbvb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gregbvb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:nose-outline" /></template>
