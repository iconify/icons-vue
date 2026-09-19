<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd6kdgv8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rd6kdgv8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:sub" /></template>
