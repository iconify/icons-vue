<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cac-zsbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cac-zsbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:receipt-subtract" /></template>
