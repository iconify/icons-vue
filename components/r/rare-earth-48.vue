<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e43ajkbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e43ajkbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rare-earth-48" /></template>
