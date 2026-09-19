<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxl4ujboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cxl4ujboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:nerve-outline" /></template>
