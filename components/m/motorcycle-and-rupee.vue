<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnebnwxmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mnebnwxmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-and-rupee" /></template>
