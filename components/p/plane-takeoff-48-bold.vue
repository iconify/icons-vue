<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddu1i-bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ddu1i-bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plane-takeoff-48-bold" /></template>
