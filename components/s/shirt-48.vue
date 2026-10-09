<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc9z0ibda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uc9z0ibda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shirt-48" /></template>
