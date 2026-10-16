<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-1w69bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-1w69bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:three-phase-20" /></template>
