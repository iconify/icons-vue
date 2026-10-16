<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0im2rdhh.css';
import '../../css/q/qa5f_6hbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q0im2rdhh"/><path class="qa5f_6hbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tower-section-48-bold" /></template>
