<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcopg4bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fcopg4bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:reservoir-48-bold" /></template>
