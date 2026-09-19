<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi42pobrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mi42pobrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xpm" /></template>
