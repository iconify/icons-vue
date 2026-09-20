<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcrk4e8vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qcrk4e8vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:prisma-16" /></template>
