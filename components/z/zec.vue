<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8oxywb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i8oxywb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:zec" /></template>
