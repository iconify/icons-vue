<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lugoebbye.css';
import '../../css/e/e55annuph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lugoebbye"/><path class="e55annuph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signature-48-bold" /></template>
