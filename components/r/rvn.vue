<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugi7pebyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ugi7pebyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:rvn" /></template>
