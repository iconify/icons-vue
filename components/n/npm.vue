<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8h_d6hpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y8h_d6hpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:npm" /></template>
