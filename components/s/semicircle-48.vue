<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwets-bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bwets-bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:semicircle-48" /></template>
