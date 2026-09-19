<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxj3tdbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":641,"height":512};
const content = `<path class="fxj3tdbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:upwork" /></template>
