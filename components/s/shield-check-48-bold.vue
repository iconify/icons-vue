<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce0cywmuu.css';
import '../../css/x/xnv-ktb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ce0cywmuu"/><path class="xnv-ktb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-check-48-bold" /></template>
