<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izjyqdbgb.css';
import '../../css/f/fqvg1ojpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="izjyqdbgb"/><path class="fqvg1ojpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smartphone-vibrate-48-bold" /></template>
