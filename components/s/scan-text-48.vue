<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d54-v5bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d54-v5bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scan-text-48" /></template>
