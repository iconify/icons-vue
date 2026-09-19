<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hozfo_wji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hozfo_wji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:pasl" /></template>
