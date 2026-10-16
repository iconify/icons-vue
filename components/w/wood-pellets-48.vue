<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcjmwhbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dcjmwhbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wood-pellets-48" /></template>
