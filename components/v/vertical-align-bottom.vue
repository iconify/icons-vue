<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7rsbabga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e7rsbabga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:vertical-align-bottom" /></template>
