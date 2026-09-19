<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkv75fisb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fkv75fisb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tornado" /></template>
