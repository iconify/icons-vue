<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a21g7ybtt.css';
import '../../css/m/m7bn_dgjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a21g7ybtt"/><path class="m7bn_dgjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:u1" /></template>
