<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-x0-ybls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p-x0-ybls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:yoyow" /></template>
