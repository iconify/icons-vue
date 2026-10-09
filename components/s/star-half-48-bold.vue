<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/domb1qbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="domb1qbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:star-half-48-bold" /></template>
