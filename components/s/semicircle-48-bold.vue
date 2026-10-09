<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k10y5ab2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k10y5ab2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:semicircle-48-bold" /></template>
