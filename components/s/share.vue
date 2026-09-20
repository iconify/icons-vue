<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckpei60ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ckpei60ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:share" /></template>
