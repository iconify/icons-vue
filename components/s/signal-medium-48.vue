<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3dr6cpiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w3dr6cpiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-medium-48" /></template>
