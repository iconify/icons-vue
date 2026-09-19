<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezhm6ccnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="ezhm6ccnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:speech" /></template>
