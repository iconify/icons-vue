<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4apv2b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g4apv2b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:typst" /></template>
