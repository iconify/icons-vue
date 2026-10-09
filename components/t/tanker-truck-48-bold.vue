<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz3__6bfa.css';
import '../../css/a/af-u6v27p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fz3__6bfa"/><path class="af-u6v27p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tanker-truck-48-bold" /></template>
