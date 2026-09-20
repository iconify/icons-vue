<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la9cs-bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="la9cs-bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:snow-flake" /></template>
