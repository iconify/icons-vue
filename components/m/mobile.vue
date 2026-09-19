<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6vm-2wrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z6vm-2wrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mobile" /></template>
