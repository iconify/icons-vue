<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xin55vtfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xin55vtfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:pac" /></template>
