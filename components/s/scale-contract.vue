<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx606acgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="sx606acgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:scale-contract" /></template>
