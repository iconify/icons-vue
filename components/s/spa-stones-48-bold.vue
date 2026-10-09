<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy03lmbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gy03lmbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spa-stones-48-bold" /></template>
