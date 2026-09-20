<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbtm7uq1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="pbtm7uq1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:menu-down-fill" /></template>
