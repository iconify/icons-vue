<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma-okvf7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ma-okvf7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ribbon2x-outline" /></template>
