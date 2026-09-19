<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk-frxrct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yk-frxrct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-clear-format" /></template>
