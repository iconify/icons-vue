<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-p8jbcsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e-p8jbcsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:tooth-outline" /></template>
