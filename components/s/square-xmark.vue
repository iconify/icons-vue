<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diaox2bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="diaox2bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-xmark" /></template>
