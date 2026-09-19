<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsryrpiyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xsryrpiyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:vtho" /></template>
