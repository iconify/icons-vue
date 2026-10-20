<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbnsb3bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fbnsb3bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sparkle-48-bold" /></template>
