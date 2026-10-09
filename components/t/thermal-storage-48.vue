<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf74hnsol.css';
import '../../css/e/e215zmbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nf74hnsol"/><path class="e215zmbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermal-storage-48" /></template>
