<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_x41mbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e_x41mbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:previous" /></template>
