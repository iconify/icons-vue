<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3j6ezyms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3j6ezyms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mining-helmet" /></template>
