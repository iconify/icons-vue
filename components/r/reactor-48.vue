<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cht574biq.css';
import '../../css/y/yhb26obxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cht574biq"/><path class="yhb26obxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:reactor-48" /></template>
