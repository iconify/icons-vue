<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fikox4b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fikox4b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:toc" /></template>
