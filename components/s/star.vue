<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb7bx9bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1050,"height":1000};
const content = `<path class="sb7bx9bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:star" /></template>
