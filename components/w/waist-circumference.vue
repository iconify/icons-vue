<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz8x56pxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fz8x56pxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:waist-circumference" /></template>
