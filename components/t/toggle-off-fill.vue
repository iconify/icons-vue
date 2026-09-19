<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wczda7yij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wczda7yij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:toggle-off-fill" /></template>
