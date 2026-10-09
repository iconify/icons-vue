<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d97ksobub.css';
import '../../css/q/qa7qb6t-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d97ksobub"/><path class="qa7qb6t-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sunrise-20" /></template>
