<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqs3_qb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wqs3_qb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:square-small2x-outline" /></template>
